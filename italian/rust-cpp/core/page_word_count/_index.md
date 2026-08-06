---
title: "page_word_count"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce il conteggio delle parole nella pagina specificata nel PDF-document."
type: docs
url: /it/rust-cpp/core/page_word_count/
---

_Restituisce il conteggio delle parole nella pagina specificata nel PDF-document._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
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

    // Restituisci il conteggio delle parole nella pagina specificata
    let count = pdf.page_word_count(page_number)?;

    // Stampa il conteggio delle parole
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```