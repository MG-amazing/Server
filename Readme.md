# 毕业设计

## 1.server端部署

拉取代码

```bash
https://github.com/MG-amazing/hioshop-server-master.git
```

配置数据库链接信息

打开项目文件

```
src/common/config/database.js
```

修改mysql数据库用户名及密码

创建数据库

```sql
create database hiolabsDB
```

运行sql脚本至hiolabsDB架构中

```bash
npm install
```

```bash
npm run start
```

## 2.ElectronPC端部署

拉取代码

```bash
https://github.com/MG-amazing/hioshop-admin.git
```

安装依赖

```bash
cnpm install 
```

处理bug

依次在项目中找到

node_modules/element-ui/packages/form/src/label-wrap.vue

将23行代码改为以下代码

```js
return ('<div class="el-form-item__label-wrap" style={style}>{ slots }</div>');
```

该错误是由于element-ui底层错误与项目代码无关

运行

```bash
npm run dev
```

输入

123

123456

登录系统

