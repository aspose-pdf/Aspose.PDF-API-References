---
title: "replace_text"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يستبدل النص."
type: docs
url: /ar/rust-cpp/organize/replace_text/
---

_يستبدل النص._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // استبدال النص في PDF-document
    pdf.replace_text("PDF", "TXT")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```