# 前言

废品交易系统是一个基于SSM框架的Java Web项目，旨在为用户提供一个方便快捷的废品回收与交易平台。通过此系统，用户可以轻松发布废品信息、查询废品价格、下单交易等。本项目遵循社会主义核心价值观，倡导绿色环保，推动资源循环利用。

# 内容介绍

本项目主要包括用户注册登录、废品分类、发布废品信息、搜索废品、下单交易等功能。系统采用前后端分离的设计模式，前端负责展示用户界面，后端负责处理业务逻辑和数据库交互。以下为项目的主要模块：

1. 用户模块：注册、登录、修改个人信息等。
2. 废品分类模块：展示各类废品及其价格。
3. 发布模块：用户可发布废品信息，包括废品名称、图片、价格等。
4. 搜索模块：用户可根据关键词、分类等条件搜索废品。
5. 交易模块：用户可下单购买废品，支持订单查询、取消订单等功能。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为废品分类模块的Service层代码示例：

```java
@Service
public class CategoryService {

    @Autowired
    private CategoryMapper categoryMapper;

    public List<Category> getAllCategories() {
        return categoryMapper.selectAll();
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/340356/20/8840/155799/68c2c5c2F17eef9d8/d0b36ff6e0c6e151.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332672/8/12211/35377/68c2c59aF1ae5eed3/f5c3a627f1e296b5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337845/7/9727/98724/68c2c59aFf969f2db/b62ca7321c2f1293.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334730/19/12130/100290/68c2c59bFca2fe19f/4a41b76b656f45ab.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/342786/28/2321/42969/68c2c59bFa6a9388f/15cfb9c995929255.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/346091/9/2274/25614/68c2c59cFafbbfa83/2696c0dc7bf4c52c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326691/39/18997/120891/68c2c59cF5910a15f/e3d1f9b69fdfd3b2.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348833/15/1782/32932/68c2c59cF8d778f23/3447938be6dcbcd0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346593/17/1934/41207/68c2c59dFc956f6d8/636d1db0bf40257f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331125/13/12107/25963/68c2c59dF1cdb4e83/f96333c585ff46b4.jpg)

