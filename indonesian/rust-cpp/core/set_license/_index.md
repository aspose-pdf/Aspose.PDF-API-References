---
title: "set_license"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengatur lisensi menggunakan nama file."
type: docs
url: /id/rust-cpp/core/set_license/
---

_Mengatur lisensi menggunakan nama file._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Atur lisensi dengan nama file
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Sekarang Anda dapat bekerja dengan dokumen PDF berlisensi
    // ...

    Ok(())
}

```