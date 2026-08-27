---
title: "page_is_blank"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisci se la pagina è vuota nel PDF-document."
type: docs
url: /it/rust-cpp/core/page_is_blank/
---

_Restituisci pagina vuota nel PDF-document._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Specifica il numero di pagina (indice a partire da 1)
    let page_number = 1;

    // Restituisci pagina vuota nel PDF-document
    let is_blank = pdf.page_is_blank(page_number)?;

    // Stampa se la pagina specificata è vuota
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```