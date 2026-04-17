# Swing Management Tool

Daily Prestart Safety Meeting Management Dashboard for Tivan Limited.

## Quick Start

1. **View the dashboard:** Open `index.html` in your browser
2. **Access live version:** https://tp-tvn.github.io/Swing-management-tool/

## File Structure

```
├── index.html              - Main dashboard (Daily Prestart Meeting)
├── config/
│   └── app-config.json     - App configuration and metadata
├── data/
│   ├── sessions.json       - Meeting sessions
│   └── meetings.csv        - Historical meeting data
├── docs/
│   ├── TEAM_GUIDE.docx     - Team setup guide
│   └── TEAM_GUIDE_TEMPLATE.dotx - Template for guides
└── attachments/
    └── weekly-reports/     - Weekly safety reports (PDFs)
```

## Data Sync

Files are automatically synced hourly to SharePoint via GitHub Actions.

- **GitHub → SharePoint:** Every hour at :15 minutes
- **Version Control:** All changes tracked in Git
- **Updates:** Real-time when new data is added

## Contributing

1. Add/update files in the repo
2. Commit changes
3. Push to `main` branch
4. GitHub Actions handles sync automatically

## Access Points

- **Dashboard:** https://tp-tvn.github.io/Swing-management-tool/
- **GitHub:** https://github.com/tp-tvn/Swing-management-tool
- **SharePoint:** (URL provided by admin)
