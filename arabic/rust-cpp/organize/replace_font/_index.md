---
title: "replace_font"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يستبدل الخط في مستند PDF-document."
type: docs
url: /ar/rust-cpp/organize/replace_font/
---

_يستبدل الخط في مستند PDF-document._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // استبدال الخط في PDF-document.
    pdf.replace_font("Helvetica", "Courier")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```