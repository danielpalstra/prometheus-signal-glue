

## Send test requests

Send an alert to alertmanager.

```shell
curl -H "Content-Type: application/json" -d '[{"labels":{"alertname":"TestAlert1"}}]' localhost:9093/api/v1/alerts
```
