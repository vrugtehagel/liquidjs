---
title: json_pase
---

{% since %}v10.16.4{% endsince %}

Convert inline JSON strings to their values through `JSON.parse()`.

Input
```liquid
{% assign hash = '{"foo": "bar"}' | json_parse %}
{{ hash.foo }}
```

Output
```text

bar
```
