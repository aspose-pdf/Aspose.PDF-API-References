---
title: "page_to_svg"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ الصفحة المحددة كصورة SVG-image."
type: docs
url: /ar/rust-cpp/convert/page_to_svg/
---

_يقوم بتحويل وحفظ الصفحة المحددة كصورة SVG-image._

```rust
pub fn page_to_svg(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // قم بتحويل وحفظ الصفحة المحددة كصورة Svg-image
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```