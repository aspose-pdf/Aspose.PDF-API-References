---
title: "remove_text_footers"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove i piè di pagina di testo dal documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_text_footers/
---

_Rimuove i piè di pagina di testo dal documento PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Rimuovi i piè di pagina di testo dal documento PDF
    pdf.remove_text_footers()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```