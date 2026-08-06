---
title: "remove_text_headers"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل رؤوس النص من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_text_headers/
---

_يزيل رؤوس النص من PDF-document._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // إزالة رؤوس النص من PDF-document
    pdf.remove_text_headers()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```