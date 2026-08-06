---
title: "remove_tables"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل الجداول من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_tables/
---

_يزيل الجداول من PDF-document._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // أزل الجداول من PDF-document
    pdf.remove_tables()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```