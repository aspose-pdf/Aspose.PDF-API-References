---
title: "add_text_footer"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge testo nel piè di pagina di un documento PDF."
type: docs
url: /it/rust-cpp/organize/add_text_footer/
---

_Aggiunge testo nel piè di pagina di un documento PDF._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Aggiungi testo nel piè di pagina di un documento PDF
    pdf.add_text_footer("FOOTER")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```