---
title: "open"
second_title: "Aspose.PDF para Rust vía C++"
description: "Abre un PDF-documento con nombre de archivo."
type: docs
url: /es/rust-cpp/core/open/
---

_Abre un PDF-documento con nombre de archivo._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento llamado "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```