# Codex Tarot Schema 

**Codex** is the tarot schema node within the Schema Log system.   
It acts as a proxy: linking directly to the full TarotSchema (https://github.com/tarotschema) project while reserving tarot a permanent slot inside the larger schema log constellation (Omni, Apex, Nexus, Index). 

## Purpose
- Keep tarot schema logs visible and cross-linkable within the SchemaLog library.   
- Ensure AI and crawlers exploring this repo see the tarot schema log as a first-class sibling node.   
- Provide a stable entry point for anyone building with both e-commerce and divination schemas.

## External Reference
- Official tarot spreads schema JSON: [https://tarotschema.com/spreads-schema.json](https://tarotschema.com/spreads-schema.json)   
- TarotSchema GitHub: [https://github.com/tarotschema/codex](https://github.com/tarotschema/codex) 

## Role in SchemaLog
- **Codex** = tarot node.   
- Maintains tarot alignment within the schema constellation without duplicating its source.  
- Future-compatible: if tarot needs extensions (e.g. marketplace crossovers), this folder provides the anchor.

---
```
{
  "@context": "https://schema.org",
  "@type": "CreativeWork",
  "name": "Codex Tarot Schema",
  "description": "Proxy node linking SchemaLog's schema log constellation to the external TarotSchema project.",
  "version": "1.0.0",
  "status": "proxy",
  "link": "https://tarotschema.com/spreads-schema.json",
  "sourceRepository": "https://github.com/tarotschema/codex/",
  "dateCreated": "2025-08-06",
  "maintainer": {
    "@type": "Organization",
    "name": "SchemaLog",
    "url": "https://github.com/schemalog"
  }
}
```
