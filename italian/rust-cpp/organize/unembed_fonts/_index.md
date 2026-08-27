---
title: "unembed_fonts"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove i font da un documento PDF."
type: docs
url: /it/rust-cpp/organize/unembed_fonts/
---

_Rimuove i font da un documento PDF._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Rimuovi i font da un documento PDF
    pdf.unembed_fonts()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```