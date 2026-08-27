---
title: "page_grayscale"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحوّل صفحة إلى أبيض وأسود."
type: docs
url: /ar/rust-cpp/organize/page_grayscale/
---

_يقوم بتحويل صفحة إلى أبيض وأسود._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
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

    // تحويل الصفحة إلى أبيض وأسود
    pdf.page_grayscale(1)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```