---
title: "flatten"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Appiattisce il documento PDF."
type: docs
url: /it/rust-cpp/organize/flatten/
---

_Appiattisce il documento PDF._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
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

    // Restituisci il contenuto del PDF-document come testo semplice
    let txt = pdf.extract_text()?;

    // Stampa il testo estratto
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```