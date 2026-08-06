---
title: "page_crop"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقص صفحة."
type: docs
url: /ar/rust-cpp/organize/page_crop/
---

_يقص صفحة._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // قص صفحة
    pdf.page_crop(1, 1.0)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```