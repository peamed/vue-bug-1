# demo

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### process
```
PS：This project is the smallest project created by Vue cli tool. Please open it first and then decide whether to close it;
1：git clone https://github.com/peamed/vue-bug-1.git(已经是最小项目了，通过vue-cli创建的，没有业务代码)；
2：npm install
3：npm run serve
4：打开本地服务链接：http://localhost:8080/
5：点击页面的home路由按钮
6：再点击页面的about路由按钮
7：再点击home路由按钮，回到home页面
8：再打开您的代码编辑工具，编辑HomeView.vue文件，如在mounted钩子函数中新增一行代码，然后点击保存运行
9：在浏览器中就会出现：runtime-core.esm-bundler.js?d2dd:5483 Uncaught (in promise) TypeError: parentComponent.ctx.deactivate is not a function
```
