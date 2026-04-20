# StreamSaver MITM Site

这个仓库用于托管自有的 `StreamSaver.js` 中转页，给用户脚本中的批量下载流程使用。

部署后页面地址：

- `https://streamsaver-mitm-site.von.im/mitm.html`

需要一起保留的文件：

- `mitm.html`
- `sw.js`

如果你要在本地脚本中替换默认地址，请把：

```js
https://jimmywarting.github.io/StreamSaver.js/mitm.html?version=2.0.0
```

替换成：

```js
https://streamsaver-mitm-site.von.im/mitm.html?version=2.0.0
```
