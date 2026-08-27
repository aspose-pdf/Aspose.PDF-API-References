---
title: "export_xfdf"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XFDF مع اسم الملف."
type: docs
url: /ar/rust-cpp/convert/export_xfdf/
---

_تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XFDF مع اسم الملف._

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
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

    // تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XFDF
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```