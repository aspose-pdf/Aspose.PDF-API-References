---
title: "remove_images"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل الصور من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_images/
---

_يزيل الصور من PDF-document._

```rust
pub fn remove_images(&self) -> Result<(), PdfError>
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

    // إزالة الصور من PDF-document
    pdf.remove_images()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_images.pdf")?;

    Ok(())
}

```