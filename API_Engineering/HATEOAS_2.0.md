# 超媒體與自主發現 (HATEOAS 2.0)

## 簡介
HATEOAS 2.0 旨在讓 AI 代理人能夠自主學習使用新的 API，無需人手動調整。

## 自主發現流程
1. **資源發現**：代理人通過超媒體格式發現可用的 API 資源。
2. **請求形成**：根據發現的資源動態生成請求。

```go
func DiscoverAPI(endpoint string) {
    response := GET(endpoint)
    // 解析資源並學習
}
``` 

---