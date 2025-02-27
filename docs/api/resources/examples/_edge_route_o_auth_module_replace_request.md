<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"provider":{"google":{"client_id":"client-id","client_secret":"client-secret","email_addresses":["alan@example.com"],"scopes":["profile","email","https://www.googleapis.com/auth/userinfo.email"]}}}' \
https://api.ngrok.com/edges/https/edghts_2tcUZz04TmT44nNqkYq1JRoAAei/routes/edghtsrt_2tcUa2b7Q6WaSvHznSdFBYPvbjI/oauth
```
