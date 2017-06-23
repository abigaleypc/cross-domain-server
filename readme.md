### 项目介绍

这是模拟启动两个服务器，他们都是`localhost`，但端口不同。采用这种方式模拟跨域问题

### 目录结构

```
.
├── JSONP
│   ├── port58023
│   │   ├── index.html
│   │   ├── package.json
│   │   ├── test.js
│   │   └── test.txt
│   └── port8080
│       ├── index.html
│       ├── package.json
│       ├── test.js
│       └── test.txt
├── XHR
│   ├── port58023
│   │   ├── index.html
│   │   ├── package.json
│   │   ├── test.js
│   │   └── test.txt
│   └── port8080
│       ├── index.html
│       ├── package.json
│       ├── test.js
│       └── test.txt
└── readme.md
```

### 操作方式

`XHR` 文件夹中
* `cd XHR/port8080`进入该子项目，启动服务器 `live-server`
* `cd XHR/port58023`进入该子项目，启动服务器 `live-server`

### 访问方式

* [http://127.0.0.1:58023/XXX](http://127.0.0.1:58023/XXX) ,其中 `XXX`代表该文件夹下的文件，如 [http://127.0.0.1:58023/test.js](http://127.0.0.1:58023/test.js)

