---
title: "get_meta_info"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il valore delle informazioni meta del PDF-document."
type: docs
url: /it/rust-cpp/core/get_meta_info/
---

_Restituisce il valore delle informazioni meta del PDF-document._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ottieni il valore delle informazioni meta del PDF-document
    let author = pdf.get_meta_info("Author")?;

    // Stampa il risultato
    println!("Author: {}", author);

    Ok(())
}

```