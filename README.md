# Techies-Match
Techies-Match

#### **1️⃣ Locally (For Running Tests on Your Machine)**

```bash


ACCESS_TOKEN="your-secure-access-token" \
newman run ./postman/Techies-match.postman_collection.json \
  -e ./postman/env_postman_environment.json \
  --env-var "accessToken=$ACCESS_TOKEN" \
  --reporters cli,html,json \
  --reporter-json-export test_reports/newman-report.json \
  --reporter-html-export test_reports/newman-report.html`
```
