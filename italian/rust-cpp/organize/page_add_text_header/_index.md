---
title: "page_add_text_header"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge testo nell'intestazione della pagina."
type: docs
url: /it/rust-cpp/organize/page_add_text_header/
---

_Aggiunge testo nell'intestazione della pagina._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi testo nell'intestazione della pagina
    pdf.page_add_text_header(1, "HEADER")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```