---
title: "extract_text"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il contenuto del PDF-document come testo semplice."
type: docs
url: /it/rust-cpp/core/extract_text/
---

_Restituisce il contenuto del PDF-document come testo semplice._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
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