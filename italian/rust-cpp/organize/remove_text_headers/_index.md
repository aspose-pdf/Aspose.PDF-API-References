---
title: "remove_text_headers"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove le intestazioni di testo dal documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_text_headers/
---

_Rimuove le intestazioni di testo dal documento PDF._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Rimuovi le intestazioni di testo dal documento PDF
    pdf.remove_text_headers()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```