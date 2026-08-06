---
title: "remove_hidden_text"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove il testo nascosto dal documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_hidden_text/
---

_Rimuove il testo nascosto dal documento PDF._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Rimuovi il testo nascosto dal documento PDF
    pdf.remove_hidden_text()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```