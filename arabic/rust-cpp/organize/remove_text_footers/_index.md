---
title: "remove_text_footers"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل تذييلات النص من مستند PDF."
type: docs
url: /ar/rust-cpp/organize/remove_text_footers/
---

_يزيل تذييلات النص من مستند PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // إزالة تذييلات النص من مستند PDF
    pdf.remove_text_footers()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```