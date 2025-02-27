<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-27T10:08:31Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tcUYqMEHfJDuMODPhC0pvdXBh4",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tcUYqMEHfJDuMODPhC0pvdXBh4"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tcUZSexulBUGjhcRst0v0pMi4q",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-27T10:08:31Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tcUZSexulBUGjhcRst0v0pMi4q",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-27T10:08:30Z",
			"hostport": "fdadaa8580c0.ngrok.paid:443",
			"id": "ep_2tcUZP5tdg0JBN595NoVaZWipdJ",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tcUWnHgw90WDfHf7Z05eSvHSqG",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://fdadaa8580c0.ngrok.paid",
			"tunnel": {
				"id": "tn_2tcUZP5tdg0JBN595NoVaZWipdJ",
				"uri": "https://api.ngrok.com/tunnels/tn_2tcUZP5tdg0JBN595NoVaZWipdJ"
			},
			"tunnel_session": {
				"id": "ts_2tcUZIPr1eP9Fq3oUhwoqkxVDjm",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tcUZIPr1eP9Fq3oUhwoqkxVDjm"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-27T10:08:30Z",
			"upstream_url": "http://localhost:80",
			"url": "https://fdadaa8580c0.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-27T10:08:27Z",
			"domain": {
				"id": "rd_2tcUYqMEHfJDuMODPhC0pvdXBh4",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tcUYqMEHfJDuMODPhC0pvdXBh4"
			},
			"edge": {
				"id": "edgtls_2tcUYqTKCTAPkFnnV1RzMGKPo1v",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tcUYqTKCTAPkFnnV1RzMGKPo1v"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tcUYpPtEz8voIwzbzyqACS1x7n",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-27T10:08:27Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
