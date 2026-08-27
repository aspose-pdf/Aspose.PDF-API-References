---
title: "save_svg_zip"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ مستند PDF المفتوح مسبقًا كأرشيف SVG."
type: docs
url: /ar/rust-cpp/convert/save_svg_zip/
---

_يقوم بتحويل وحفظ مستند PDF المفتوح مسبقًا كأرشيف SVG._

```rust
pub fn save_svg_zip(&self, filename: &str) -> Result<(), PdfError>
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

    // تحويل وحفظ مستند PDF المفتوح مسبقًا كأرشيف SVG
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```