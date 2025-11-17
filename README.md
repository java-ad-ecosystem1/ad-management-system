# 匿名用户精准广告投放生态系统

## 团队成员与分工
| 姓名     | 负责模块                | 技术栈与核心职责                                                                 |
|----------|-------------------------|----------------------------------------------------------------------------------|
| 杜一帆   | 广告管理网站            | Servlet + JSP + MySQL，开发广告投放API、跨站Cookie追踪、广告商管理后台          |
| 韩晴     | 购物网站                | Servlet + JSP + Vue.js，开发商品展示、广告位嵌入、用户行为上报逻辑              |
| 刘宇晴   | 视频发布分享网站        | Servlet + JSP + Vue.js，开发视频播放、贴片广告、视频行为数据采集                |
| 朱紫月   | 新闻网站                | Servlet + JSP + Vue.js，开发新闻分类、广告集成、跨站行为串联                    |

## 技术选型（JavaWeb 传统架构）

### 后端技术
- **核心框架**: Servlet 4.0 + JSP 2.3
- **JDK版本**: JDK 17
- **服务器**: Apache Tomcat 11.x
- **数据库**: MySQL 8.0 + JDBC
- **会话管理**: HttpSession + Cookie
- **构建工具**: Maven

### 前端技术  
- **核心框架**: Vue.js 2.x 或 jQuery（根据复杂度选择）
- **UI库**: Element UI 或 Bootstrap
- **构建工具**: 传统script引入或Webpack

### 开发环境
- **IDE**: IntelliJ IDEA Ultimate（支持JavaWeb）
- **服务器**: 内嵌Tomcat或外置Tomcat
- **数据库工具**: MySQL Workbench/Navicat

## 项目结构（每个模块独立）

### 广告管理网站 (杜一帆)
