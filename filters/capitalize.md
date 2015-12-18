---
title: capitalize
---

`capitalize` makes the first character of your string capitalized.

```liquid
{% raw %}
{{ "title" | capitalize }}
{% endraw %}
```

```text
Title
```

`capitalize` only capitalizes the first character of the string, so subsequent words are not affected:

 ```liquid
{% raw %}
{{ "my great title" | capitalize }}
{% endraw %}
```

```text
My great title
```
