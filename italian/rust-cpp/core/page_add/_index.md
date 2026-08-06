---
title: "page_add"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge una nuova pagina al documento PDF."
type: docs
url: /it/rust-cpp/core/page_add/
---

_Aggiunge una nuova pagina al documento PDF._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi una nuova pagina nel documento PDF
    pdf.page_add()?;

    // Salva il PDF-document precedentemente aperto
    pdf.save()?;

    Ok(())
}

```