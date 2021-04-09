# Slide is Tree

## Introduction

Do you know [org-tree-slide](https://github.com/takaxp/org-tree-slide) ?

## How?

Write down your slide as a tree-style YAML+markdown.

### Don't design it

- Don't think about pagination
- Don't think alignment for images

### Example

Slide is just a big tree.

```markdown
---
title: How to breakfast
author: @cympfh
---

- What is breakfast?
    - By Wikipedia:
        - >-
            Breakfast is the first meal of the day eaten after waking up, usually in the morning.[1]
            The word in English refers to breaking the fasting period of the previous night.[2]
    - Examples:
        - ![banana](./banana.png)
        - ![apple](apple.png)
- Breakfast Stat
    - >-
        | What   | Ratio (%) |
        |--------|-----------|
        | Banana | 30.0      |
        | Apple  | 20.0      |
        | Others | 50.0      |
```


