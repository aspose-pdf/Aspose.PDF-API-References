---
title: "optimize_resource"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottimizza le risorse del documento PDF."
type: docs
url: /it/rust-cpp/organize/optimize_resource/
---

_Ottimizza le risorse del documento PDF._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // Ottimizza le risorse del documento PDF
    pdf.optimize_resource()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```