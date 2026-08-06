---
title: "baru"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membuat PDF-dokumen baru."
type: docs
url: /id/rust-cpp/core/new/
---

_Membuat PDF-dokumen baru._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buat dokumen PDF baru
    let pdf = Document::new()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```