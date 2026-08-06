---
title: "page_add_text_footer"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge testo nel piè di pagina della pagina."
type: docs
url: /it/rust-cpp/organize/page_add_text_footer/
---

_Aggiunge testo nel piè di pagina della pagina._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi testo nel piè di pagina della pagina
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```