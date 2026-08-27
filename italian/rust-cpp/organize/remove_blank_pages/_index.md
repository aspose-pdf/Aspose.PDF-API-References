---
title: "remove_blank_pages"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove le pagine vuote dal PDF-document."
type: docs
url: /it/rust-cpp/organize/remove_blank_pages/
---

_Rimuove le pagine vuote dal PDF-document._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Rimuovi le pagine vuote dal documento PDF
    pdf.remove_blank_pages()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```