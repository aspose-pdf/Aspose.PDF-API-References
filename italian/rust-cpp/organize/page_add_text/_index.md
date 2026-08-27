---
title: "page_add_text"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge testo a una pagina."
type: docs
url: /it/rust-cpp/organize/page_add_text/
---

_Aggiunge testo a una pagina._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi testo sulla pagina
    pdf.page_add_text(1, "added text")?;

    // Salva il PDF-document precedentemente aperto
    pdf.save()?;

    Ok(())
}

```