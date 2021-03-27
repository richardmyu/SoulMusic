# Soul Music

### 环境运行

克隆完成以后：

1. `npm install`，安装包；

2. 在 NeteaseCloudMusicApi 文件内启动 `node app.js`；

3. 然后在 `server` 中启动 `server.js`；

4. `npm run dev`；

### 技术栈

- react
- react-router
- redux
- nodejs
- express

### 项目结构

```
|
├─ NeteaseCloudMusicApi———– 网易云 API（这也是一个库，因而没有上传，即 github 中不可见）
│  └─app.js——————– API 入口
|
├─ server———– 项目后台
│  └─mock——————– 后台入口
│
├─src——– 项目前台
│  │
│  ├─api————– api接口
│  │
│  ├─ components ———– 公共组件
│  │  │
│  │  ├─ Tab ————– 底部菜单组件
│  │  ├─ NavBar ————– 头部组件
│  │  ├─ TabsControl ———– 首页tab切换组件
│  │  └─ Protected ———– 登陆保护组件
│  │
│  ├─ container ——– 页面级组件
│  │  │
│  │  ├─ Home —————–首页
│  │  │  │
│  │  │  ├─ Carousel ————– 首页轮播图
│  │  │  │
│  │  │  │─ Music ———————– 发现音乐页
│  │  │  │  │
│  │  │  │  ├─ Recommend ———————– 推荐音乐页
│  │  │  │  ├─ RankingList —————– 排行榜页
│  │  │  │  ├─ SongList ————————– 歌单列表页
│  │  │  │  └─ NewMusicList ————– 最新音乐列表页
│  │  │  │
│  │  │  └─ Search ——————–搜索音乐组件
│  │  │
│  │  ├─ MyMusic ——————————–我的音乐页
│  │  ├─ SongMenuDetail ———–歌单详情页
│  │  ├─ Single ———————————–单曲播放页
│  │  ├─ Login ————————————–登录页
│  │  ├─ Register——————————–注册页
│  │  └─ Profile ——————————–个人中心页
│  │
│  ├─ images ——————– 静态图片
│  │
│  ├─ store ———————– redux store文件夹
│  │  │
│  │  ├─ actions ——– 各页面actions集合文件
│  │  │  ├─ home ———————– 首页action
│  │  │  └─ session ————– 处理登陆注册的action
│  │  │
│  │  └─ reducers ————– reducers 文件夹
│  │      ├─ home ————————– 处理首页各组件状态的reducer
│  │      └─ session —————– 处理登陆注册状态的reducer
│  │
│  └─ style ———————– 公共样式
│
└─ utils ———– 工具库

```

[2020-12-11] This is an old peoject, i'm preparing to update.

[NeteaseCloudMusicApi](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=neteasecloudmusicapi)
