---
title: "set_background"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengatur warna latar belakang dokumen PDF menggunakan nilai RGB."
type: docs
url: /id/rust-cpp/organize/set_background/
---

_Mengatur warna latar belakang dokumen PDF menggunakan nilai RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Atur warna latar belakang dokumen PDF menggunakan nilai RGB
    pdf.set_background(200, 100, 101)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```