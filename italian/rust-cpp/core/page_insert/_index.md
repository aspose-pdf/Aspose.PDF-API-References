---
title: "page_insert"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Inserisce una nuova pagina nella posizione specificata nel PDF-document."
type: docs
url: /it/rust-cpp/core/page_insert/
---

_Inserisce una nuova pagina nella posizione specificata nel PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Inserisci una nuova pagina nella posizione specificata nel PDF-document
    pdf.page_insert(1)?;

    // Salva il PDF-document precedentemente aperto
    pdf.save()?;

    Ok(())
}

```