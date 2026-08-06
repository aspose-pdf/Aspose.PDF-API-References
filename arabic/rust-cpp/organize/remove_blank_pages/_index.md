---
title: "remove_blank_pages"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل الصفحات الفارغة من مستند PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_blank_pages/
---

_يزيل الصفحات الفارغة من مستند PDF-document._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // إزالة الصفحات الفارغة من PDF-document
    pdf.remove_blank_pages()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```