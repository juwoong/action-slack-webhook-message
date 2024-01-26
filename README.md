# Action Slack Message
Send message inclues commit message, commiter, commit hash and branch

```yaml
inputs:
  slack_webhook_url: 
    description: 'Slack Webhook URL'
    required: true
  short_sha:
    description: 'Short SHA'
    required: true
```