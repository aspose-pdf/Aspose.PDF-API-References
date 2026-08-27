---
title: "character_count"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il conteggio dei caratteri nel documento PDF."
type: docs
url: /it/rust-cpp/core/character_count/
---

_Restituisce il conteggio dei caratteri nel documento PDF._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
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

    // Restituisci il conteggio dei caratteri nel documento PDF
    let count = pdf.character_count()?;

    // Stampa il conteggio dei caratteri
    println!("Character count: {}", count);

    Ok(())
}

```