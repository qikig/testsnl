# testsnl
项目结构
# Web 应用
# 类库

Core：

‌Models‌：数据模型。

‌Services‌：业务逻辑服务。

‌Repositories‌：数据访问层。

‌Helpers‌：辅助方法或工具类。


# test 文件夹结构

‌UnitTests‌：单元测试。

‌IntegrationTests‌：集成测试。

‌FunctionalTests‌：功能测试

# lib 文件夹结构

第三方库可以直接放在 lib 文件夹中

#项目结构

MyApp/

├── src/

│   ├── MyApp.Web/

│   │   ├── Controllers/

│   │   ├── Models/

│   │   ├── Views/

│   │   ├── wwwroot/

│   │   ├── appsettings.json

│   │   ├── Program.cs

│   │   └── Startup.cs

│   └── MyApp.Core/

│   └── MyApp.Models/

│   └── MyApp.Services/

│   └── MyApp.Repositories/

    └── MyApp.Helpers/
    
├── test/

│   └── MyApp.Tests/

│       ├── UnitTests/

│       └── IntegrationTests/

├── lib/ (或通过 NuGet 管理)

├── .gitignore

├── README.md

├── global.json

└── Dockerfile (如有需要)
