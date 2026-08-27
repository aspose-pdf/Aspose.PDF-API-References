---
title: "page_add_text"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف نصًا إلى صفحة."
type: docs
url: /ar/rust-cpp/organize/page_add_text/
---

_يضيف نصًا إلى صفحة._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة نص إلى الصفحة
    pdf.page_add_text(1, "added text")?;

    // احفظ مستند PDF-document المفتوح مسبقًا
    pdf.save()?;

    Ok(())
}

```