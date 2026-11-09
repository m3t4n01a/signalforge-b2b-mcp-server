# SignalForge B2B & AI Extraction MCP Server

Unified Model Context Protocol (MCP) server exposing 5 production B2B & AI extraction tools:

- **Company Domain to B2B Email & Tech Stack Enricher (DNS + Web OSINT)** (`willowy_catamaran_fco/b2b-domain-email-tech-scraper`)
- **LinkedIn & Google Jobs Scraper + Automatic B2B Company Email Enricher** (`willowy_catamaran_fco/google-linkedin-jobs-scraper`)
- **Tech Startup ATS Jobs, Tech Stack & Hiring Intent Scraper (Greenhouse API)** (`willowy_catamaran_fco/startup-ats-jobs-b2b-scraper`)
- **Reddit B2B Buying Intent & Competitor Mention Monitor** (`willowy_catamaran_fco/reddit-posts-b2b-scraper`)
- **YouTube Transcript, Subtitles & Telemetry Scraper for RAG / LLM Agents** (`willowy_catamaran_fco/youtube-transcript-extractor`)

## Quick Start (Claude Desktop / Cursor)
```bash
npx -y @apify/actors-mcp-server --actors willowy_catamaran_fco/b2b-domain-email-tech-scraper,willowy_catamaran_fco/google-linkedin-jobs-scraper,willowy_catamaran_fco/startup-ats-jobs-b2b-scraper,willowy_catamaran_fco/reddit-posts-b2b-scraper,willowy_catamaran_fco/youtube-transcript-extractor
```
