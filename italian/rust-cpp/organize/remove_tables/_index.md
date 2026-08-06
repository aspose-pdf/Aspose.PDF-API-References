---
title: "remove_tables"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove le tabelle dal PDF-document."
type: docs
url: /it/rust-cpp/organize/remove_tables/
---

_Rimuove le tabelle dal PDF-document._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // Rimuovi le tabelle dal PDF-document
    pdf.remove_tables()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```