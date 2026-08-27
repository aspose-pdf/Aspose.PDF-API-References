---
title: "repair"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ripara il PDF-document."
type: docs
url: /it/rust-cpp/organize/repair/
---

_Ripara il PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Ripara PDF-document
    pdf.repair()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```