---
title: "page_to_png"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan halaman yang ditentukan sebagai gambar PNG."
type: docs
url: /id/rust-cpp/convert/page_to_png/
---

_Mengonversi dan menyimpan halaman yang ditentukan sebagai gambar PNG._

```rust
pub fn page_to_png(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Konversi dan simpan halaman yang ditentukan sebagai gambar Png
    pdf.page_to_png(1, 100, "sample_page1.png")?;

    Ok(())
}

```