---
title: "add_page_num"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف رقم الصفحة إلى مستند PDF."
type: docs
url: /ar/rust-cpp/organize/add_page_num/
---

_يضيف رقم الصفحة إلى مستند PDF._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // إضافة رقم الصفحة إلى PDF-document
    pdf.add_page_num()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```