##project structure

    ├── README.md
    ├── bin                                    #express 启动入口
    │   └── www
    ├── config                                   #环境配置，以后的一些环境配置都可以放这里
    │   └── storeConfig.js
    ├── dist                                     #压缩打包后的目录
    │   └── store
    │       ├── index.html
    │       └── js
    ├── public                                    #express node多页面静态资源目录
    │   └── images                             #express node 图片 （暂时未用）
    │   └── javascript                          #express node javascript文件（暂时未用）
    │   └── stylesheets                      #express node style文件 （暂时未用）
    │   └── favicon.ico                      favicon文件
    ├── routes                                    #express node controller文件
    ├── package.js                               #打包执行完成后的一些后续操作
    ├── package.json                             #node项目包依赖配置文件
    ├── readModuleConfig.js                      #读取单个配置信息
    ├── src
    │   ├── common                               #公用部分
    │   │   ├── common.js                        #公用js、
    │   │   ├── common.scss                      #公用scss
    │   │   ├── reset.scss                       #reset scss
    │   │   └── size.scss                        #自适应scss
    │   └── store                                #单个项目的文件夹
    │       ├── actions                          #action 放这里
    │       │   └── home
    │       │       ├── aboutAction.jsx
    │       │       └── indexAction.jsx
    │       ├── components                        #公用控件
    │       │   ├── Alert.jsx
    │       │   ├── Alert.scss
    │       │   ├── Dialog.jsx
    │       │   ├── Dialog.scss
    │       │   ├── Loading.jsx
    │       │   ├── Loading.scss
    │       │   ├── Mask.jsx
    │       │   ├── Mask.scss
    │       │   └── size.scss
    │       ├── const                              #常量
    │       │   └── home
    │       │       ├── IndexTypes.jsx
    │       │       └── aboutTypes.jsx
    │       ├── css                                #css
    │       │   └── home
    │       │       ├── about.scss
    │       │       └── app.scss
    │       ├── images                             #图片
    │       │   └── test.jpeg
    │       ├── reducers                           #reducer
    │       │   └── home
    │       │       ├── about.jsx
    │       │       └── index.jsx
    │       ├── store                              #store
    │       │   └── home
    │       │       ├── aboutStore.jsx
    │       │       └── indexStore.jsx
    │       └── view                               #单个页面存放
    │           ├── home
    │           │   ├── about.jsx
    │           │   └── index.jsx
    │           └── router.jsx                     #路由
    ├── template                                   #单页面文件的html模板
    │   ├── server.template.html
    │   └── test.template.html
    ├── util.js                                    #node工具类
    ├── webpack.config.js                          #打包公共配置
    ├── webpack.production.config.js               #打包配置
    └── webpack.server.config.js                   #热更新服务器配置