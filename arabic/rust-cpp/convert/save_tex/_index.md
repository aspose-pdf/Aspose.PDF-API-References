---
title: "save_tex"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة TeX-document."
type: docs
url: /ar/rust-cpp/convert/save_tex/
---

_يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة TeX-document._

```rust
pub fn save_tex(&self, filename: &str) -> Result<(), PdfError>
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

    // قم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة TeX-document
    pdf.save_tex("sample.tex")?;

    Ok(())
}

```