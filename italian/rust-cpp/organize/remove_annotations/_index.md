---
title: "remove_annotations"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove le annotazioni dal documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_annotations/
---

_Rimuove le annotazioni dal documento PDF._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Rimuovi le annotazioni dal documento PDF
    pdf.remove_annotations()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```