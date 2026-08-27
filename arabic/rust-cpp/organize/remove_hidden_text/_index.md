---
title: "remove_hidden_text"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل النص المخفي من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_hidden_text/
---

_يزيل النص المخفي من PDF-document._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // إزالة النص المخفي من PDF-document
    pdf.remove_hidden_text()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```