---
title: "page_count"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il numero di pagine nel PDF-document."
type: docs
url: /it/rust-cpp/core/page_count/
---

_Restituisce il numero di pagine nel PDF-document._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // Restituisci il numero di pagine nel PDF-document
    let count = pdf.page_count()?;

    // Stampa il numero di pagine
    println!("Count: {}", count);

    Ok(())
}

```