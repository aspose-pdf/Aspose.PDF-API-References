---
title: "unembed_fonts"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يفك تضمين الخطوط في مستند PDF."
type: docs
url: /ar/rust-cpp/organize/unembed_fonts/
---

_يفك تضمين الخطوط في مستند PDF._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // فك تضمين الخطوط في مستند PDF
    pdf.unembed_fonts()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```