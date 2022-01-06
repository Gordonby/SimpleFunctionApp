# SimpleFunctionApp
Just a simple web app to consume for test deployments

## Routes

| Route | Function Name | Content Type | Description |
| ----- | ------------- | ------------ | ----------- |
| / | BasicHtmlResponse | Html | Hello world |
| /CheckAppSettings | CheckAppSettings | Html | Returns several AppSettings values as Html |
| /api/context | Context | Json | Returns traffic id from AppSettings as well as the default `name` from querystring
