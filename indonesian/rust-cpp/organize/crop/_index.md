---
title: "potong"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memotong halaman dokumen PDF."
type: docs
url: /id/rust-cpp/organize/crop/
---

_Memotong halaman dokumen PDF._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Potong halaman dokumen PDF
    pdf.crop(10.5)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```