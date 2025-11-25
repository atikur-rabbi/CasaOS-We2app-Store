# n8n - Workflow Automation Tool

n8n is a fair-code licensed workflow automation tool that allows you to automate tasks across different services and APIs.

## Features

- **Visual Workflow Editor**: Create complex automations with an intuitive drag-and-drop interface
- **200+ Integrations**: Connect to popular services like Gmail, Slack, GitHub, Airtable, and more
- **Self-hosted**: Keep your data private and secure on your own infrastructure
- **Webhook Support**: Trigger workflows via HTTP webhooks
- **Scheduling**: Run workflows on a schedule using cron expressions
- **Error Handling**: Built-in error workflows and retry mechanisms
- **Custom Code**: Execute JavaScript/Python code within your workflows

## Default Configuration

- **Port**: 5678
- **Data Directory**: /DATA/AppData/n8n/data
- **Environment**: Production

## Initial Setup

1. Access n8n at `http://your-server-ip:5678`
2. Create your first user account
3. Start building workflows!

## Environment Variables

- `N8N_PORT`: Port for the web interface (default: 5678)
- `WEBHOOK_URL`: Your webhook base URL (important for webhooks to work)
- `GENERIC_TIMEZONE`: Set your timezone (e.g., America/New_York)
- `NODE_ENV`: Node environment (production recommended)

## Using Webhooks

For webhooks to work properly, set the `WEBHOOK_URL` environment variable to your public domain:
```
WEBHOOK_URL=https://your-domain.com/
```

## Documentation

For more information, visit: https://docs.n8n.io/
