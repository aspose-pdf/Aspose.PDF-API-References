---
title: "nuovo"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Crea un nuovo documento PDF."
type: docs
url: /it/rust-cpp/core/new/
---

_Crea un nuovo documento PDF._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```