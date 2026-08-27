---
title: "page_character_count"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il conteggio dei caratteri nella pagina specificata del documento PDF."
type: docs
url: /it/rust-cpp/core/page_character_count/
---

_Restituisce il conteggio dei caratteri nella pagina specificata del documento PDF._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Specifica il numero di pagina (indice a partire da 1)
    let page_number = 1;

    // Restituisci il conteggio dei caratteri nella pagina specificata
    let count = pdf.page_character_count(page_number)?;

    // Stampa il conteggio dei caratteri
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```