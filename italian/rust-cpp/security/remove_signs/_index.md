---
title: "remove_signs"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuovi le firme dal PDF-document."
type: docs
url: /it/rust-cpp/security/remove_signs/
---

_Rimuovi le firme dal PDF-document._

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
    // Apri un PDF-document chiamato "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Rimuovi le firme dal PDF-document
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```