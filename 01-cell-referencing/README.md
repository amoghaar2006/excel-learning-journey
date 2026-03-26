# Cell Referencing in Excel

## Overview
This section covers the fundamentals of cell referencing in Excel, including relative, absolute, and mixed referencing. These concepts are essential for building dynamic and reusable formulas.

## Concepts Covered

### 1. Relative Referencing
- Cell references change automatically when the formula is dragged or copied
- Used for calculations like row-wise addition and CGPA

**Example:**
= C20 + D20

---

### 2. Absolute Referencing
- Cell reference remains fixed using `$`
- Used when a constant value (like discount rate) is applied across multiple rows

**Example:**
= B2 * (1 - $C$1)

---

### 3. Mixed Referencing
- Either row or column is fixed
- Useful for multi-directional calculations (e.g., applying different discounts across rows and columns)

**Example:**
= $E32 * (1 - I$32)

---

## Key Learnings
- Understanding how references behave when dragged
- Using `$` to control formula behavior
- Applying formulas efficiently using AutoFill
