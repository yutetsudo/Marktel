---
title: Marktel syntax reference
author: Yutetsudo
date: 28/03/2022
version: 0.1
---

# Marktel syntax reference

# Headings

```
#  Double Size
#W Double Width
#H Doubke Height
   Normal Size
```

Renders to :
<img src="assets/2022-03-28-21-20-32-image.png" title="" alt="" width="960">

## Paragraphs

For paragraph, just write normal text

```
Lorem ipsum dolor sit amet, graecis denique ei vel, at duo primis mandamus.
```

Renders to :

<img src="assets/2022-03-28-21-22-08-image.png" title="" alt="" width="960">

## Horizontal Rule

To create a thematic break, you can use : `---`

Renders to :

<img src="assets/2022-03-28-21-54-21-image.png" title="" alt="" width="960">

## Special effects

### Blink

The following snippet `** **`, render blinking text.

```
**Rendered as blinking text**
```

render to :

<img src="assets/2022-03-28-21-25-42-BLINK.gif" title="" alt="" width="960">

### Underline

The following snippet `_ _`, render underlineed text.

```
_Rendered as underlined text_
```

render to :

<img src="assets/2022-03-28-21-27-46-image.png" title="" alt="" width="960">

### Invert text

The following snippet `~~ ~~`, render inverted text.

```
~~Rendered as inverted text~~
```

render to :

<img src="assets/2022-03-28-23-02-25-image.png" title="" alt="" width="960">

## Lists

### Unordered

A list of items in which the order of the items does not explicitly matter.

```
- Lorem ipsum dolor sit amet.
- Consectetur adipiscing elit.
  - Integer molestie lorem at massa.
  - Facilisis in pretium nisl aliquet.
```

render to :

<img src="assets/2022-03-28-21-52-41-image.png" title="" alt="" width="960">

### Ordered

A list of items in which the order of items does explicitly matter.

```
1. Lorem ipsum dolor sit amet.
2. Consectetur adipiscing elit.
3. Integer molestie lorem at massa.
4. Facilisis in pretium nisl aliquet.
```

render to :

<img src="assets/2022-03-28-21-57-52-image.png" title="" alt="" width="960">
