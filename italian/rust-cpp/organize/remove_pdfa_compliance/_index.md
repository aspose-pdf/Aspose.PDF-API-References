---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove la conformità PDF/A da un documento PDF."
type: docs
url: /it/rust-cpp/organize/remove_pdfa_compliance/
---

_Rimuovi la conformità PDF/A da un documento PDF._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Rimuovi la conformità PDF/A da un documento PDF
    pdf.remove_pdfa_compliance()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```