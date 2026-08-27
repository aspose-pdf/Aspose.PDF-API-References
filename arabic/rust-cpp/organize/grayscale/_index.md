---
title: "grayscale"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحول مستند PDF إلى أبيض وأسود."
type: docs
url: /ar/rust-cpp/organize/grayscale/
---

_يحول مستند PDF إلى أبيض وأسود._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تحويل مستند PDF إلى أبيض وأسود
    pdf.grayscale()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```