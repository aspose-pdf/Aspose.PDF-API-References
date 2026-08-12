---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF para Rust vía C++"
description: "Eliminar el cumplimiento PDF/A de un documento PDF."
type: docs
url: /es/rust-cpp/organize/remove_pdfa_compliance/
---

_Eliminar el cumplimiento PDF/A de un documento PDF._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Eliminar el cumplimiento PDF/A de un documento PDF
    pdf.remove_pdfa_compliance()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```