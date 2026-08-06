---
title: "byte"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il contenuto del documento PDF come un vettore di byte."
type: docs
url: /it/rust-cpp/core/bytes/
---

_Restituisce il contenuto del documento PDF come un vettore di byte._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Restituisci il contenuto del documento PDF come un vettore di byte
    let data = pdf.bytes()?;

    // Stampa la lunghezza del vettore di byte
    println!("Length: {}", data.len());

    Ok(())
}

```