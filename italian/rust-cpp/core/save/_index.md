---
title: "save"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Salva il PDF-document precedentemente aperto."
type: docs
url: /it/rust-cpp/core/save/
---

_Salva il PDF-document precedentemente aperto._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document chiamato "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Salva il PDF-document precedentemente aperto
    pdf.save()?;

    Ok(())
}

```