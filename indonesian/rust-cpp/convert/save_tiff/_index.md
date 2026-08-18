---
title: "save_tiff"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai dokumen Tiff-document."
type: docs
url: /id/rust-cpp/convert/save_tiff/
---

_Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai dokumen Tiff-document._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **resolution_dpi** - the resolution in DPI
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

    // Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai dokumen Tiff-document
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```