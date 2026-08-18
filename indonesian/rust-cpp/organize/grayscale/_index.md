---
title: "grayscale"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dokumen PDF menjadi hitam putih."
type: docs
url: /id/rust-cpp/organize/grayscale/
---

_Mengonversi dokumen PDF menjadi hitam putih._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Konversi dokumen PDF menjadi hitam putih
    pdf.grayscale()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```