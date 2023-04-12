# -
这是一个基于 Spring Boot 和 MySQL 的图书管理系统，旨在提供一个完整的图书管理和查询平台。系统具有以下主要功能和特点：  - 图书的添加、删除、修改和查询 - 借阅和归还图书 - 图书分类和排序 - 用户身份验证和权限管理  使用的技术和工具包括：  - Spring Boot - MySQL - Thymeleaf - Bootstrap
book-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.bookmanagementsystem/
│   │   │       ├── controller/ # 控制器类
│   │   │       ├── dao/ # 数据访问对象类
│   │   │       ├── model/ # 数据模型类
│   │   │       ├── repository/ # 数据库存储库类
│   │   │       ├── service/ # 服务类
│   │   │       ├── BookManagementSystemApplication.java # 启动类
│   │   │       └── WebSecurityConfig.java # Web 安全配置类
│   │   └── resources/
│   │       ├── static/ # 静态资源文件
│   │       ├── templates/ # Thymeleaf 模板文件
│   │       ├── application.properties # 应用程序配置文件
│   │       └── data.sql # 数据库初始化数据文件
│   └── test/
│       └── java/
│           └── com.example.bookmanagementsystem/
│               ├── controller/
│               ├── dao/
│               ├── model/
│               ├── repository/
│               └── service/
└── pom.xml # Maven 项目配置文件
