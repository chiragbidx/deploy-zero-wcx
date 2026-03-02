# Calendly URL Validation

## Supplied URL
```
https://calendly.com/chirag-bidx/30min?hide_event_type_details=1&hide_gdpr_banner=1
```

## Validation Checklist

- **Protocol:** Uses HTTPS ✔️
- **Base Domain:** calendly.com ✔️
- **Username Present:** chirag-bidx ✔️
- **Event Path Present:** /30min ✔️
- **Additional Parameters:**
  - hide_event_type_details=1 (valid)
  - hide_gdpr_banner=1 (valid)
- **No unsupported or extraneous query params** ✔️
- **URL is in structure:** `https://calendly.com/{username}/{event}?{params}` ✔️
- **Works for embedding in `<iframe>` according to Calendly documentation** ✔️

## Best Practice Alignment

- Calendly officially supports this format for inline embedding.
- No modifications needed for the intended use.

## Final Status

**This Calendly URL is valid for inline embed integration.**