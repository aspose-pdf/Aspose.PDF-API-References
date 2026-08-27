---
title: "page_add_text_footer"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف النص في تذييل الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_add_text_footer/
---

_يضيف النص في تذييل الصفحة._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة نص في تذييل الصفحة
    pdf.page_add_text_footer(1, "FOOTER")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```