---
title: "فتح"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يفتح مستند PDF بالاسم المحدد."
type: docs
url: /ar/rust-cpp/core/open/
---

_يفتح مستند PDF بالاسم المحدد._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```