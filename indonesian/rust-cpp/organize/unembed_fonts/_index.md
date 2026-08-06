---
title: "unembed_fonts"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Melepaskan font dari PDF-document."
type: docs
url: /id/rust-cpp/organize/unembed_fonts/
---

_Melepaskan font dari PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Lepaskan font dari PDF-document
    pdf.unembed_fonts()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```