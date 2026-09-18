---
"hunkdiff": patch
---

`hunk session comment add` accepts `--source <label>` and `hunk session comment apply` accepts a
`source` field per stdin item, letting an agent tag which producer wrote a live comment instead of
every live comment reporting as `mcp`. Omitting it keeps the existing default.
