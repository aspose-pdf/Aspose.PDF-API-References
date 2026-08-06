---
title: "remove_signs"
second_title: "Aspose.PDF para Rust vía C++"
description: "Eliminar firmas del PDF-document."
type: docs
url: /es/rust-cpp/security/remove_signs/
---

_Eliminar firmas del PDF-document._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-document llamado "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Eliminar firmas del PDF-document
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```