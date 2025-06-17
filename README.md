# CircleCI Deploys Dashboard

## ✨ Features

### 🔍 **Advanced Semantic Search**
Query deployments using natural language and powerful operators:
- **Time ranges**: `failed between 03:00 and 03:40`
- **Status filtering**: `status:failed last 4 hours`
- **Environment targeting**: `production failures today`
- **Author tracking**: `author:fozzie last 24 hours`
- **Service-specific**: `data-archival-service @timestamp:>2025-03-20T03:00:00`

### ⚡ **SRE-Optimized for Incident Response**
- **Quick filters** for common scenarios (failures, running, production, recent)
- **Commit messages prominently displayed** for immediate context
- **Real-time status updates** with auto-refresh
- **Visual status indicators** with color-coded borders

### 🎯 **Smart Query Formats**
- **ISO 8601 timestamps**: `@timestamp:>2025-03-20T03:00:00Z`
- **Simple dates**: `@timestamp:=2025-03-19`
- **Natural language**: `last 4 hours`, `today`, `yesterday`
- **Complex multi-condition queries**: `failed environment:production between 03:00 and 03:40`


