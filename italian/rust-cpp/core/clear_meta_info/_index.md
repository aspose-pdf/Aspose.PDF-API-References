---
title: "clear_meta_info"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Cancella tutti i valori delle meta informazioni del PDF-document."
type: docs
url: /it/rust-cpp/core/clear_meta_info/
---

_Cancella tutti i valori delle meta informazioni del PDF-document._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Cancella tutti i valori delle meta informazioni del PDF-document
    pdf.clear_meta_info()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```