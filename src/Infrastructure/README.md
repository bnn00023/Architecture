Infrastructure
=================

用於實作Application所需要的Interface



Library
-----------------
- Dapper : 與DB溝通
- EntityFrameworkCore : 與DB溝通
- MongoDB.Driver.Core : 與Mongo溝通
- StackExchange.Redis : 與Redis溝通
- MiniProfiler : 紀錄各個外部操作的使用時間
- Grpc : 與別的Grpc溝通
- NSwag.ApiDescription.Client : 依Swagger檔案產生HttpClient
- Refit.HttpClientFactory : 依Interface產生HttpClient
- Polly : Retry策略
- MassTransit : 與RabbitMq溝通
- EasyCaching.Core : 實現Cache功能