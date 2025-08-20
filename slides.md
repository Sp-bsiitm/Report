---
marp: true
theme: custom
paginate: true
class: lead
---

<!-- _class: lead -->

# Product Documentation

**Email:** 24f1001384@ds.study.iitm.ac.in

---

# Overview

- Easy to maintain in version control
- Export to **PDF, PPTX, HTML**
- Uses **custom theme & styles**

---

<!-- _backgroundImage: url('images/background.png') -->
<!-- _class: lead -->

# With Background Image

This slide has a full background!

---

# Algorithmic Complexity

We can express complexities with equations:

$$ O(n \log n) $$
$$ T(n) = 2T\left(\frac{n}{2}\right) + O(n) $$

---

# Code Example

```python
def binary_search(arr, target):
    left, right = 0, len(arr)-1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
