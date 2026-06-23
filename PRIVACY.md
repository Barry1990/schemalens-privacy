# SchemaLens Privacy Policy

Effective date: 2026-06-24

SchemaLens is a desktop database client published by NX Labs. This policy describes what data the app accesses, stores, and transmits.

## Data Stored Locally

SchemaLens stores app data on the user's device, including:

- Saved MySQL and Redis connection profiles, including host, port, username, database name, and saved passwords.
- AI provider settings, including API keys when the user saves them.
- Query history, SQL favorites, and workspace preferences.
- Local schema cache files generated from connected databases.
- MCP settings and local MCP log files.

This data is stored locally in the app data directory. SchemaLens does not operate an NX Labs cloud service for this data.

## Database Access

SchemaLens connects only to database servers configured by the user. Query results, schema information, and exported files remain on the user's device unless the user explicitly saves, exports, transfers, syncs, imports, or sends that information through an enabled AI provider.

## AI Features

AI features are optional and disabled until configured by the user. If the user enables a cloud AI provider, SchemaLens may send the user's prompt, relevant SQL, database schema metadata, table names, column names, comments, and execution-plan context to the AI endpoint configured by the user. The configured AI provider processes that data under its own terms and privacy policy.

If the user configures a local Ollama endpoint, AI requests are sent to that local endpoint instead of a cloud provider.

## Network Communication

SchemaLens may communicate with:

- User-configured MySQL and Redis servers.
- User-configured AI endpoints such as OpenAI-compatible APIs, Gemini, or Ollama.

SchemaLens does not include advertising, analytics, telemetry, or tracking code.

## File Access

SchemaLens uses file picker dialogs so the user can choose files for import and choose output paths for export, backup, and generated scripts. The app writes only the files selected by the user and local app data/cache/log files required for its database-client functionality.

## Data Sharing

NX Labs does not sell user data. SchemaLens does not send data to NX Labs servers. Data is shared with third parties only when the user configures and uses third-party services, such as an AI provider or a database server controlled by the user or their organization.

## User Controls

Users can delete saved database connections, SQL favorites, query history, AI settings, MCP defaults, generated exports, and local app data from their device. Users can disable AI features by clearing or disabling their AI configuration.

## Contact

For privacy questions, contact NX Labs through the support contact listed in the Microsoft Store product page.
