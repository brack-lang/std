# std
The standard library of [brack](https://github.com/brack-lang/brack).

## ✅ Headline
std supports three levels headline. Too mush structuring disrupts blog writing.

```brack
{* H1}
{** H2}
{*** H3}
```

## ✅ Anchor Link

```brack
[@ text, url]
```

## ✅ Decoration

```brack
[* bold]
[/ Italic]
[~ strike-out line]
[_ underline]
```

## Inline code & Code block

```brack
[# inline-code]
{# language-name,
  code block
}
```

## ✅ Footnote

```brack
<^ footnote>
```

## List

### Unordered List
```brack
{ul
  item1
  item2
  {ul
    item2-1
    item2-2
  }
  item3
}
```

### Ordered List
```brack
{ol
  item1
  item2
  {ol
    item2-1
    item2-2
  }
  item3
}
```

## Table

```brack
<table
  [- col1, col2, col3],
  [- data1, data2, data3],
>
```

## Horizontal Rule

```brack
{---}
```

## ✅ Images

```brack
[img url, alt]
```
