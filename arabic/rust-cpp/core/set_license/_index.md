---
title: "set_license"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضبط الترخيص باستخدام اسم الملف."
type: docs
url: /ar/rust-cpp/core/set_license/
---

_يضبط الترخيص باستخدام اسم الملف._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // ضبط الترخيص باستخدام اسم الملف
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // الآن يمكنك العمل مع مستند PDF المرخص
    // ...

    Ok(())
}

```