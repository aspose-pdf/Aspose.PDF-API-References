---
title: "remove_javascripts"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل سكريبتات جافا من مستند PDF."
type: docs
url: /ar/rust-cpp/organize/remove_javascripts/
---

_يزيل سكريبتات جافا من مستند PDF._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // إزالة سكريبتات جافا من PDF-document
    pdf.remove_javascripts()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```