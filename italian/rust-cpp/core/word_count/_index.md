---
title: "word_count"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il conteggio delle parole nel PDF-document."
type: docs
url: /it/rust-cpp/core/word_count/
---

_Restituisce il conteggio delle parole nel PDF-document._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Restituisci il conteggio delle parole nel PDF-document
    let count = pdf.word_count()?;

    // Stampa il conteggio delle parole
    println!("Word count: {}", count);

    Ok(())
}

```