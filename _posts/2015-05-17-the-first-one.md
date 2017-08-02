---
title: "靡不有初"
categories:
  - 无远弗届 Far & Wide
tags:
  - content
  - css
  - edge case
  - lists
  - markup
---

Nested and mixed lists are an interesting beast. It's a corner case to make sure that

立志用功，如种树然。方其根芽，犹未有干。及其有干，尚未有枝。枝而后叶。叶而后花实。初种根时，只管栽培灌溉。勿作枝想。勿作叶想。勿作花想。勿作实想。悬想何益？但不忘栽培之功，怕。没有枝叶花寅。

* Lists within lists do not break the ordered list numbering order
* Your list styles go deep enough.

### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    1. ordered item
    2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    * unordered item
    * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item
  1. ordered
  2. ordered
    * unordered item
    * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item
  * unordered
  * unordered
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item
