# 基础语法参考

> [!CAUTION]
> 此页面非完全原创，源自[Github Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#referencing-external-resources)

# A first-level heading

## A second-level heading

### A third-level heading

**This is bold text**  
**This text is _extremely_ important**  
_This text is italicized_  
~~This was mistaken text~~  
This is a <sub>subscript</sub> text  
This is a <sup>superscript</sup> text  
This is an <ins>underlined</ins> text

> Text that is a quote

Use `git status` to list all new or modified files that haven't yet been committed.  
Some basic Git commands are:

```
git status
git add
git commit
```

This site was built using [GitHub Pages](https://pages.github.com/).

Insert IMAGE:
![Headimg](/HEAD.png)

## Alert

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Nested List

1. First list item
   - First nested list item
     - Second nested list item

## Task List

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

## Sheet

| 默认居左对齐 | 居中对齐 | 居右对齐 |
| ------------ | :------: | -------: |
| 内容 1       |  内容 2  |   内容 3 |
| 内容 4       |  内容 5  |   内容 6 |

## Footnote

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]:
    To add line breaks within a footnote, prefix new lines with 2 spaces.
    This is a second line.
