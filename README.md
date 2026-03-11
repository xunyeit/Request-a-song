<font style="color:#000000;">讯业软件开发/讯业酒吧点歌-java点歌系统</font>

## <font style="color:#000000;">功能概述：</font>
**<font style="color:#000000;">适用于多店点歌小程序，一店一码，多店独立后台。支持设置歌单自动刷新、支持设置时间段点歌限制。适用于酒吧、清吧等场合、提供歌手入驻、方便结算歌手收益。</font>**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215393596-cd0b3b14-4003-4bbd-bf97-e05cf099e170.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215406387-1d682113-1efc-4455-b9d4-0c17121ba318.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215416241-e65161fa-62f0-4d89-9c95-1c98905cba98.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215430937-ceb3e9c0-89c2-44e7-80bd-1c2ffa07a188.png)

<font style="color:#000000;"></font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215441817-73f95cc1-b578-46d4-ab76-87459ee2bed2.png)

## <font style="color:#000000;">用户端：</font>
**<font style="color:#000000;">用户端扫码进入店铺，小程序授权登录</font>**

**<font style="color:#000000;">艺人列表：艺人头像、查看艺人首页介绍、查看艺人歌单</font>**

**<font style="color:#000000;">热门歌曲：热门歌曲推荐、支持多选点歌</font>**

**<font style="color:#000000;">店铺资讯：资讯列表发布店铺信息</font>**

**<font style="color:#000000;">分类：快速搜索点歌、艺人歌单分类、支持多选点歌</font>**

**<font style="color:#000000;">我的：查看点歌列表、歌曲状态、账号设置、用户头像昵称手机号更换、切换艺人端</font>**

## <font style="color:#000000;">艺人端：</font>
**<font style="color:#000000;">艺人账号密码登录</font>**

**<font style="color:#000000;">一键上下班，歌手下班后歌手歌单同步隐藏</font>**

**<font style="color:#000000;">已点曲目：歌手演唱列表、手动歌曲状态</font>**

**<font style="color:#000000;">我的歌单：查看个人歌单列表、切换用户端</font>**

## <font style="color:#000000;">后台管理端</font>
**<font style="color:#000000;">后台端可自由创建分店账号密码、创建分店歌单、创建分店歌手、设置歌单自动刷新时间、设置店铺时间段点歌限制、查看店铺盈利、设置账号权限等</font>**

## <font style="color:#000000;">架构特点</font>
### <font style="color:#000000;">架构特性</font>
+ **<font style="color:#000000;">前后端分离架构，独立开发，符合主流开发模式</font>**
+ **<font style="color:#000000;">前端以Vue3+Vite为主技术，AntdV为UI界面框架</font>**
+ **<font style="color:#000000;">后端SpringBoot3为基础，MybatisPlus为数据操作框架，Redis为缓存框架</font>**
+ **<font style="color:#000000;">Maven多模块管理，插件化开发，方便安装、卸载、升级，降低耦合</font>**
+ **<font style="color:#000000;">业务模块与API抽离，模块之间便捷引用</font>**
+ **<font style="color:#000000;">数据库设计精巧，字段规范、易于扩展</font>**
+ **<font style="color:#000000;">支持国产密码算法加解密，等保测评国产项目无压力</font>**
+ **<font style="color:#000000;">支持MYSQL、ORACLE、SQLSERVER、PGSQL等主流标准结构式数据库</font>**
+ **<font style="color:#000000;">支持达梦、人大金仓、南大通用、九有、瀚高、虚谷数据库等国产数据库</font>**
+ **<font style="color:#000000;">支持中创、宝蓝德、东方通等中间件</font>**
+ **<font style="color:#000000;">支持Windows、Linux操作系统、国产操作系统部署</font>**

### <font style="color:#000000;">功能特性</font>
+ **<font style="color:#000000;">完善的系统基础功能，满足使用需求，避免重复造轮子</font>**
+ **<font style="color:#000000;">支持本地文件、阿里云文件、腾讯云文件、MINIO文件上传</font>**
+ **<font style="color:#000000;">支持本地邮件、阿里云邮件、腾讯云邮件发送</font>**
+ **<font style="color:#000000;">支持阿里云短信、腾讯云短信发送</font>**
+ **<font style="color:#000000;">B、C端双账号认证体系，会话治理各自独立</font>**
+ **<font style="color:#000000;">完善的登录日志、操作日志、异常日志等审计功能</font>**
+ **<font style="color:#000000;">完善的会话监控、数据源监控、系统监控等必备监控功能</font>**
+ **<font style="color:#000000;">支持组织机构、权限管理、定时任务、系统配置等基础功能</font>**

### <font style="color:#000000;">安全特性</font>
+ **<font style="color:#000000;">采用SaToken轻量级 Java 权限认证框架，功能强大、学习成本低</font>**
+ **<font style="color:#000000;">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0等认证模式</font>**
+ **<font style="color:#000000;">增强的RBAC权限设计，资源于接口独立授权，更加灵活</font>**
+ **<font style="color:#000000;">支持按钮级别细粒度独立授权，界面按钮动态展示</font>**
+ **<font style="color:#000000;">支持API接口注解式、路由拦截式鉴权，防止越界访问</font>**
+ **<font style="color:#000000;">独创的数据范围机制，每个接口都可以配置不同数据范围</font>**
+ **<font style="color:#000000;">支持限流防抖，防重复提交，有效阻止脏数据产生</font>**
+ **<font style="color:#000000;">密码、手机、身份证号等使用国密算法加密传输、加密存储，数据更安全</font>**
+ **<font style="color:#000000;">操作日志使用SM2进行完整性保护，满足安全审计要求</font>**

### <font style="color:#000000;">界面特性</font>
+ **<font style="color:#000000;">Vue3 + Vite为基础，AntdV为界面UI框架，视觉风格清新简洁</font>**
+ **<font style="color:#000000;">精细化设计，注重界面的每一处细节，操作轻松友好</font>**
+ **<font style="color:#000000;">暗黑风格、经典菜单、双排菜单、多页签、目录坞、主题切换等功能应有尽有</font>**
+ **<font style="color:#000000;">统一的网络框架、API接口拦截框架，拿来即可上手</font>**



**<font style="color:#000000;">联系交流</font>**

**<font style="color:#000000;">公司官网：</font>**[**https://www.xunyeit.com**](https://www.xunyeit.com)

**<font style="color:#000000;">案例库：</font>**[**https://cms.xunyeit.com/**](https://cms.xunyeit.com/)

**<font style="color:#000000;">交流微信：</font>**<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773215490989-6c65b882-5a68-4b17-9dbe-280a06c1d260.png)

