---
title: truncatewords
---

`truncate` shortens a string down to the number of words passed as a parameter. If the number of words specified is less than the number of words in the string, an ellipsis (...) is appended to the string.

```liquid
{% raw %}
{{ "Ground control to Major Tom." | truncatewords: 3 }}
{% endraw %}
```

```text
{{ "Ground control to Major Tom." | truncatewords: 3 }}
```
