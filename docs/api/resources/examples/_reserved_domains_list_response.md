<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-27T10:08:11Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3ipxvh59bvwjzdrao.local-ngrok-cname.com",
			"created_at": "2025-02-27T10:08:10Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tcUX0vDTLqH2cerVOVJUv2fOLq",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tcUX0vDTLqH2cerVOVJUv2fOLq"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tcUWqk04Qn9RZnSeK2zhnCunql",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tcUWqk04Qn9RZnSeK2zhnCunql"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3ipxvh59bvwjzdrao.local-ngrok-cname.com",
			"created_at": "2025-02-27T10:08:10Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tcUWmSGp6b5FpdflSDDcZFQvdM",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tcUWmSGp6b5FpdflSDDcZFQvdM"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
