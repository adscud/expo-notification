To send a notification:

```
curl -H "Content-Type: application/json" -X POST "https://exp.host/--/api/v2/push/send" -d '{
  "to": "ExponentPushToken[TOKEN]",
  "title":"hello",
  "body": "world"
}'
```

Where `TOKEN` is your device token.
