# storage-lock 管理界面

静态页面，每 3 秒读取一次 HTTP 管理接口并展示持有者、剩余租约和等待队列。

```bash
python3 -m http.server 8090
```

默认请求同源的 `/locks`。指向其他管理服务时使用 `index.html?api=http://host:8080/locks`。
