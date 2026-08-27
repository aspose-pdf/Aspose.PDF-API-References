---
title: "grayscale"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte il documento PDF in bianco e nero."
type: docs
url: /it/rust-cpp/organize/grayscale/
---

_Converte il documento PDF in bianco e nero._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti il documento PDF in bianco e nero
    pdf.grayscale()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```