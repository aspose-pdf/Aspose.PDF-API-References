---
title: "page_replace_text"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يستبدل النص في الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_replace_text/
---

_يستبدل النص في الصفحة._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // استبدال النص على الصفحة
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```