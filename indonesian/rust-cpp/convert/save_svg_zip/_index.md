---
title: "save_svg_zip"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai SVG-archive."
type: docs
url: /id/rust-cpp/convert/save_svg_zip/
---

_Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai SVG-archive._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai SVG-archive
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```