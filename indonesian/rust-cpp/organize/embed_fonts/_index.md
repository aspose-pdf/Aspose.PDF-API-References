---
title: "embed_fonts"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menyematkan font pada dokumen PDF."
type: docs
url: /id/rust-cpp/organize/embed_fonts/
---

_Menyematkan font pada dokumen PDF._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // Menyematkan font pada dokumen PDF
    pdf.embed_fonts()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```