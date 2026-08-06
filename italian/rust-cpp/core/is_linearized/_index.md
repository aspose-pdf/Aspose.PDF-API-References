---
title: "is_linearized"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce un valore che indica se il documento è linearizzato."
type: docs
url: /it/rust-cpp/core/is_linearized/
---

_Restituisce un valore che indica se il documento è linearizzato._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ottieni un valore che indica se il documento è linearizzato
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```