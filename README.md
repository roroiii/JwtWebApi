# README.md

## .NET 6 Web API 與 JWT Token 驗證

此專案為使用 .NET 6 Web API 與 JWT Token 驗證的範例程式碼，可以協助開發人員了解如何在 .NET 6 Web API 中實現 JWT Token 驗證。

### 如何使用

1. 下載或複製此專案程式碼到本地端。
2. 使用 Visual Studio 2019 或以上版本開啟專案。
3. 在 Visual Studio 中按下 F5 開始執行專案。
4. 使用 Postman 或其他類似工具進行 API 測試。

### 程式碼結構

- `Controllers`: 包含 API 控制器。
- `Models`: 包含定義的資料模型。
- `Services`: 包含 JWT Token 相關的服務。

### 使用到的套件

- `Microsoft.AspNetCore.Authentication.JwtBearer`: 用於實現 JWT Token 驗證。
- `Microsoft.IdentityModel.Tokens`: 用於 JWT Token 的建立和驗證。

### 參考資料

- [JWT.IO](https://jwt.io/)
- [Microsoft Docs: Authenticate with JWT in a web API](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/accjwt?view=aspnetcore-6.0)
