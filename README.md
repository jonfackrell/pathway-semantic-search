# Semantic Search

## YAML Shapes Accepted

### Single-document file

```yaml
title: Intro to Widgets
url: https://docs.example.com/intro
text: |
  Widgets are small but mighty...
```

### Array of documents

```yaml
- title: Intro to Widgets
  url: https://docs.example.com/intro
  text: |
    ...
- title: Advanced Widgets
  url: https://docs.example.com/advanced
  text: |
    ...
- title: Intro to Widgets
  url: https://docs.example.com/intro
  text: |
    ...
- title: Advanced Widgets
  url: https://docs.example.com/advanced
  text: |
    ...
```

### Multi-document YAML (— separators)

```yaml
---
title: Intro to Widgets
url: https://docs.example.com/intro
text: |
  ...
---
title: Advanced Widgets
url: https://docs.example.com/advanced
text: |
  ...
```

### Documents: wrapper

```yaml
documents:
  - title: Intro to Widgets
    url: https://docs.example.com/intro
    text: |
      ...
  - title: Advanced Widgets
    url: https://docs.example.com/advanced
    text: |
      ...
```