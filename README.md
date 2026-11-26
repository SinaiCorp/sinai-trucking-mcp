# Sinai Trucking Solutions — public MCP integration documentation

Operated by Sinai Group LLC. North Carolina dump truck hauling.

- Website: https://sinaicorp.com/trucking/
- MCP endpoint: https://sinaicorp.com/mcp
- Transport: Streamable HTTP
- Registry name: `com.sinaicorp/trucking`
- Version: 1.4.0
- Privacy: https://sinaicorp.com/privacy.html

## Tools

Read-only: `get_company_profile`, `get_services`, `get_service_areas`, `get_fleet_capabilities`, `check_fleet_availability`, `request_quote`, `request_subcontracting`, `check_project_eligibility`.

Write action: `submit_project_inquiry`. Discover the current input schema with `tools/list`. Show the exact contact and project data and obtain explicit permission before submitting via Formspree. Never infer consent. A successful response confirms acceptance by the form provider, not email receipt, availability, pricing or booking. Identity is not verified. Do not retry automatically after an uncertain delivery. Duplicate and rate limits apply. Use the official project bid form if necessary: https://sinaicorp.com/trucking/project-bid/.

This repository contains public integration documentation only, not the private server implementation. No live fleet availability or binding quotes are provided.
