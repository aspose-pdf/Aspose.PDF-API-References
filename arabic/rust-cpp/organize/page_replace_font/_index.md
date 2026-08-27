---
title: "page_replace_font"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يستبدل الخط في الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_replace_font/
---

_يستبدل الخط في الصفحة._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // استبدال الخط في الصفحة
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```