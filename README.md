# Soul Music

### 环境运行

- git clone 地址；
- 找到 NeteaseCloudMusicApi 文件,剪切到其他文件内,解压 NeteaseCloudMusicApi 文件,使用 cmd 命令 `node app.js` 运行；
- 回到 Soul Music 文件内 `npm install` 配置文件；
- 然后启动 `server.js`；
- `npm run dev`；


### 技术栈

- react
- react-router
- redux
- nodejs
- express

### 项目结构

```
|
├─ NeteaseCloudMusicApi———– 网易云 API
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
