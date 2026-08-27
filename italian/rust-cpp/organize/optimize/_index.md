---
title: "optimize"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottimizza il contenuto del PDF-document."
type: docs
url: /it/rust-cpp/organize/optimize/
---

_Ottimizza il contenuto del PDF-document._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Ottimizza il contenuto del PDF-document
    pdf.optimize()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```