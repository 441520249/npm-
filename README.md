# npm-

Vue报错：command failed: npm install --loglevel error --registry=https://registry.npm.taobao.org

使用vue-cli创建项目是报了如下错误： command failed: npm install --loglevel error --registry=https://registry.npm.taobao.org --disturl=https://npm.taobao.org/dist

## 总结了有以下几个解决方式：
首先确保所用到的vue-cli，npm，node等，版本要高一些。然后尝试以下方法：
- 1.npm install chromedriver --chromedriver_cdnurl=http://cdn.npm.taobao.org/dist/chromedriver
- 2.npm cache clean --force 清除npm的缓存
