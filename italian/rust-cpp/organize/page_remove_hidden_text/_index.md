---
title: "page_remove_hidden_text"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove il testo nascosto nella pagina."
type: docs
url: /it/rust-cpp/organize/page_remove_hidden_text/
---

_Rimuove il testo nascosto nella pagina._

```rust
pub fn page_remove_hidden_text(&self, num: i32) -> Result<(), PdfError>
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

    // Rimuovi il testo nascosto nella pagina
    pdf.page_remove_hidden_text(1)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_remove_hidden_text.pdf")?;

    Ok(())
}

```