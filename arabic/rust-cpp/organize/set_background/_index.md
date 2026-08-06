---
title: "set_background"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضبط لون خلفية مستند PDF باستخدام قيم RGB."
type: docs
url: /ar/rust-cpp/organize/set_background/
---

_يضبط لون خلفية مستند PDF باستخدام قيم RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // ضبط لون خلفية مستند PDF باستخدام قيم RGB
    pdf.set_background(200, 100, 101)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```