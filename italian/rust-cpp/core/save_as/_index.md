---
title: "save_as"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Salva il PDF-document precedentemente aperto con un nuovo nome di file."
type: docs
url: /it/rust-cpp/core/save_as/
---

_Salva il PDF-document precedentemente aperto con un nuovo nome di file._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Salva il PDF-document con un nuovo nome di file
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```