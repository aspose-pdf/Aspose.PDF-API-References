---
title: "page_add_page_num"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف رقم الصفحة على الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_add_page_num/
---

_يضيف رقم الصفحة على الصفحة._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة رقم الصفحة إلى الصفحة
    pdf.page_add_page_num(1)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```