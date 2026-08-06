---
title: "export_xml"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XML مع اسم الملف."
type: docs
url: /ar/rust-cpp/convert/export_xml/
---

_تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XML مع اسم الملف._

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
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

    // تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى مستند XML
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```