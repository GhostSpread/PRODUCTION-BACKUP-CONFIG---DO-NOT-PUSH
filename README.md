{
  "//": "🛑 PRODUCTION BACKUP CONFIG - DO NOT PUSH",
  "env": "production",
  "aws_access_key_id": "AKIAIOSFODNN7EXAMPLE",
  "aws_secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY",
  "aws_region": "us-east-1",
  "heroku_api_key": "3a8f0d4e-dfe0-4b9c-a23e-6a7d5aa5example",
  "gcp_service_account": {
    "type": "service_account",
    "project_id": "ghost-prod-internal",
    "private_key_id": "23a4f8e6cde29fexample",
    "private_key": "-----BEGIN PRIVATE KEY-----\nMIIEv...EXAMPLEKEY\n-----END PRIVATE KEY-----\n",
    "client_email": "ghost-prod@ghost-prod-internal.iam.gserviceaccount.com",
    "client_id": "112233445566778899001",
    "auth_uri": "https://accounts.google.com/o/oauth2/auth",
    "token_uri": "https://oauth2.googleapis.com/token"
  },
  "slack_webhook": "https://hooks.slack.com/services/T00000000/B00000000/XXXXXXXXXXXXXXXXXXXXXXXX",
  "db": {
    "host": "172.16.254.3",
    "port": 5432,
    "user": "admin_ghost",
    "pass": "9d3g7$Vnp*L2a"
  },
  "internal_ping": "curl -X POST https://ghostline-drift-mirror.netlify.app/ping?src=awsprod",
  "_note": "This config is for legacy backup access, remove after cutover to SSM."
}
