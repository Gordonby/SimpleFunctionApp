# Simple Function App

Just a simple c# Azure Function App to use for test deployments

.NET6 / v4 Functions Runtime

## Routes

| Route | Function Name | Content Type | Description |
| ----- | ------------- | ------------ | ----------- |
| / | BasicHtmlResponse | Html | Hello world |
| /CheckAppSettings | CheckAppSettings | Html | Returns several AppSettings values as Html |
| /api/context | Context | Json | Returns traffic id from AppSettings as well as the default `name` from querystring
