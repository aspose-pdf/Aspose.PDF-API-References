---
title: "save_as"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menyimpan dokumen PDF yang sebelumnya dibuka dengan nama file baru."
type: docs
url: /id/rust-cpp/core/save_as/
---

_Menyimpan dokumen PDF yang sebelumnya dibuka dengan nama file baru._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
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
    // Buat dokumen PDF baru
    let pdf = Document::new()?;

    // Simpan dokumen PDF dengan nama file baru
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```