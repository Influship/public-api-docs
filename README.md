# Influship API Documentation

Streamlined documentation for the Influship API MVP launch.

## Structure

```
docs/
├── index.mdx                 # Homepage
├── quickstart.mdx           # 5-minute getting started guide
├── implementation-status.mdx # What's working vs coming soon
├── guides/
│   └── authentication.mdx   # API key authentication
├── api-reference/
│   ├── introduction.mdx     # API overview
│   └── data-formats.mdx     # Data types and formats
├── examples/                # Code examples (existing)
├── support/
│   ├── faq.mdx             # Common questions
│   ├── troubleshooting.mdx # Issue resolution
│   └── contact.mdx         # Support contact info
└── docs.json               # Navigation configuration
```

## Key Features

- **Focused on MVP**: Only documents what's actually working
- **Clear status indicators**: ✅ Working, ⚠️ Coming Soon
- **Minimal cognitive load**: Simple navigation, essential content only
- **Quick start path**: 5-minute setup guide
- **Proper expectations**: Implementation status page

## Deployment

1. Deploy the MVP OpenAPI spec to your server
2. Update the OpenAPI URL in `docs.json` if needed
3. Deploy the docs to your hosting platform
4. Test with early customers

## Files Removed for MVP

The following files were removed to focus on essential content:

- Complex guide files (billing, performance, webhooks, etc.)
- Changelog and roadmap pages
- Advanced feature documentation

These can be added back as features are implemented.
