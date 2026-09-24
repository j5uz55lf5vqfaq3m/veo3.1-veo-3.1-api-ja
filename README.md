# Veo 3.1 API 日本語ガイド（veo-3.1 / veo3.1）

> 従量課金、最低 1 ドルから、OpenAI 互換エンドポイント。 **default $0.07; extend $0.07; 4K $0.57**

**[模型页](https://go.apimart.ai/k-6b6722) · [实时价格](https://go.apimart.ai/k-fcec85) · [获取 API Key](https://go.apimart.ai/k-d32dd4)**

## 料金（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `default` | $0.07 |
| `extend` | $0.07 |
| `4K` | $0.57 |
| `EXTEND-4K` | $0.57 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"veo3.1-lite","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本リポジトリはサードパーティ中継サービス APIMart の利用ガイドです。
