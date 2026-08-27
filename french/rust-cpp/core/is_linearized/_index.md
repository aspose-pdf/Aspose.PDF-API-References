---
title: "is_linearized"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtient une valeur indiquant si le document est linéarisé."
type: docs
url: /fr/rust-cpp/core/is_linearized/
---

_Obtient une valeur indiquant si le document est linéarisé._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Obtenir une valeur indiquant si le document est linéarisé
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```