---
title: "export_fdf"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يصدّر من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند FDF مع اسم الملف."
type: docs
url: /ar/rust-cpp/convert/export_fdf/
---

_يصدّر من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند FDF مع اسم الملف._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند FDF
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```