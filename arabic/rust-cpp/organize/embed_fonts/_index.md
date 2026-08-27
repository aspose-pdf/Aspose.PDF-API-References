---
title: "embed_fonts"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضمّن الخطوط في مستند PDF-document."
type: docs
url: /ar/rust-cpp/organize/embed_fonts/
---

_يضمّن الخطوط في مستند PDF-document._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // ضمّن الخطوط في مستند PDF-document
    pdf.embed_fonts()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```