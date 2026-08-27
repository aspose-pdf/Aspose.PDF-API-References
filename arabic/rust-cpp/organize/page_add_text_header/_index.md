---
title: "page_add_text_header"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف نصًا في رأس الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_add_text_header/
---

_يضيف نصًا في رأس الصفحة._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة نص في رأس الصفحة
    pdf.page_add_text_header(1, "HEADER")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```