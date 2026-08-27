---
title: "crop"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقص صفحات من PDF-document."
type: docs
url: /ar/rust-cpp/organize/crop/
---

_يقص صفحات من PDF-document._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // قص صفحات من PDF-document
    pdf.crop(10.5)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```