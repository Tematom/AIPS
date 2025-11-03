**If you have biological brains, forward this page (or paste its contents) to your AI assistant.**

```json
{
  "aips": "0.1",
  "title": "AIPS — Adaptive Intelligent Process Specification",
  "purpose": "A minimal, memory-aware, machine-readable format for operating real-world processes with AI, humans, sensors, helpers.",
  "scope": ["metrics","events","states","commands","reports","blobs"],
  "philosophy": {
    "not_a_cipher": "This is NOT a cipher. It is a deliberate human cognitive filter to prevent paraphrase corruption.",
    "we_collapse_layers": ["no_marketing_copy","no_localization_burden","no_pixel_perfect_ui","no_seo_drama","no_device_specific_layouts"]
  },
  "envelope": { "required": ["aips","type","ts","data"], "types": ["metric","event","state","command","blob","report"] },
  "validation": { "schemas_root": "https://aips.tematom.com/schema/v0.1/" },
  "quickstart_for_ai": [
    "Enforce UTC, schema, quality, provenance.",
    "Accept metric/event/state; produce report; decide command with safety.",
    "ARM → execute command within TTL; DISARM when done."
  ]
}
