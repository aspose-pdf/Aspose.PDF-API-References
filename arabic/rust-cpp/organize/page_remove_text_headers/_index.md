---
title: "page_remove_text_headers"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل رؤوس النص في الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_remove_text_headers/
---

_يزيل رؤوس النص في الصفحة._

```rust
pub fn page_remove_text_headers(&self, num: i32) -> Result<(), PdfError>
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
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إزالة رؤوس النص في الصفحة
    pdf.page_remove_text_headers(1)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_remove_text_headers.pdf")?;

    Ok(())
}

```