# Hi, I'm sure

一名关注真实产品落地的后端 / 小程序全栈开发者。  
我喜欢把校园里的具体问题做成可上线、可维护、有人真正使用的系统，而不是只停留在 Demo。

<p>
  <a href="https://github.com/sure141319/wx-school-app">
    <img src="https://img.shields.io/badge/Project-Campus%20Trade-2f6f4e?style=flat-square" alt="Campus Trade" />
  </a>
  <a href="https://github.com/zreason-group/PocketAHUT">
    <img src="https://img.shields.io/badge/Project-PocketAHUT-1f6feb?style=flat-square" alt="PocketAHUT" />
  </a>
  <img src="https://img.shields.io/badge/Java-17-b07219?style=flat-square&logo=openjdk&logoColor=white" alt="Java 17" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.3-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/WeChat%20Mini%20Program-07C160?style=flat-square&logo=wechat&logoColor=white" alt="WeChat Mini Program" />
</p>

## About Me

- 主要方向：Java 后端、微信小程序、校园服务类产品
- 常用技术：Spring Boot、MyBatis、MySQL、Redis、MinIO、Flyway、JWT、VitePress
- 工程关注：接口契约、权限安全、数据迁移、图片上传处理、缓存、测试与 CI
- 项目特点：做过已上线微信小程序，也参与过团队协作型校园服务项目

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>校园闲置集市 Campus Trade</h3>
      <p>
        面向安徽工业大学学生的校园闲置信息公告栏，包含微信小程序、Spring Boot 后端、图片审核台、商品管理和公告管理后台。
      </p>
      <p>
        <a href="https://github.com/sure141319/wx-school-app">Repository</a>
        ·
        <a href="https://www.ahut-campus.site">Production API / Site</a>
      </p>
      <p>
        <strong>Tech:</strong> Java 17, Spring Boot 3.3, MyBatis, MySQL, Redis, MinIO, Flyway, JWT, WeChat Mini Program
      </p>
      <ul>
        <li>设计商品发布、搜索筛选、详情浏览、上下架和审核状态流转</li>
        <li>实现 JWT 认证、BCrypt 密码加密、登录失败锁定、验证码频控和管理员权限控制</li>
        <li>接入 MinIO 对象存储，处理图片上传、格式校验、WebP 变体和上传对象生命周期</li>
        <li>用 Flyway 管理数据库迁移，并通过 Maven Test、契约测试和 GitHub Actions 做质量门禁</li>
      </ul>
      <p align="center">
        <img src="./assets/campus-trade-qrcode.jpg" width="170" alt="校园闲置集市微信小程序码" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>口袋安小工 PocketAHUT</h3>
      <p>
        面向安徽工业大学学生的一站式校园生活服务平台，覆盖课表、成绩、考试、空教室、电费、食堂、校园新闻等常用场景。
      </p>
      <p>
        <a href="https://github.com/zreason-group/PocketAHUT">Repository</a>
        ·
        <a href="https://github.com/zreason-group/PocketAHUT/releases/">Releases</a>
      </p>
      <p>
        <strong>Role:</strong> 开发 & 测试贡献者
        <br />
        <strong>Tech:</strong> VitePress, pnpm, GitHub Actions, WeChat Mini Program ecosystem
      </p>
      <ul>
        <li>参与校园服务平台的功能开发、测试和文档完善</li>
        <li>围绕教务学习、宿舍电费、空教室、食堂、体测等高频场景整理功能说明</li>
        <li>维护 VitePress 文档站，让新用户和贡献者更快理解平台能力</li>
        <li>在团队项目中进行协作开发，关注可读文档、问题反馈和上线体验</li>
      </ul>
      <p align="center">
        <img src="./assets/pocket-ahut-qrcode.jpg" width="170" alt="口袋安小工微信小程序码" />
      </p>
    </td>
  </tr>
</table>

## Engineering Highlights

| Area | What I Have Built |
| --- | --- |
| Backend API | Spring Boot REST API, unified response model, OpenAPI / Swagger, DTO contract tests |
| Security | JWT auth, BCrypt password hashing, login lockout, verification-code rate limiting, admin-only audit APIs |
| Data | MySQL schema design, Flyway migrations, Redis cache, H2 test database |
| Storage | MinIO object storage, image validation, HEIC / HEIF / WebP processing, upload lifecycle cleanup |
| Mini Program | WeChat native mini program pages, product flows, production release and QR-code access |
| Quality | Maven tests, GitHub Actions, verification scripts, API contract maintenance |

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-17-b07219?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge" alt="MyBatis" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/WeChat%20Mini%20Program-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat Mini Program" />
  <img src="https://img.shields.io/badge/VitePress-5C73E7?style=for-the-badge&logo=vitepress&logoColor=white" alt="VitePress" />
</p>

## What I Care About

- 把需求边界讲清楚：平台做什么、不做什么，都要写进文档和代码约束里
- 把系统做完整：不只写接口，也考虑认证、审核、存储、迁移、测试和上线
- 把项目做可信：README、接口文档、质量门禁和可扫码访问的线上结果，都应该经得起别人点开看

## GitHub

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=sure141319&show_icons=true&hide_title=true&hide_border=true&theme=transparent" alt="sure141319 GitHub stats" />
</p>

<!--
可选增强:
1. 在 GitHub Profile 侧边栏补充真实姓名、学校、城市、邮箱或简历链接。
2. 如果有个人博客，可以把博客链接加到 About Me 或 GitHub 区域。
3. 首页仓库建议命名为 sure141319，并将本 README.md 与 assets/ 一起提交。
-->
