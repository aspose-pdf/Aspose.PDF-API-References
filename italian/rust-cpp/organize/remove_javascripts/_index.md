---
title: "remove_javascripts"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove gli script Java dal documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_javascripts/
---

_Rimuove gli script Java dal documento PDF._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // Rimuovi gli script Java dal documento PDF
    pdf.remove_javascripts()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```