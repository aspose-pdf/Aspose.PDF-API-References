---
title: "set_background"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Imposta il colore di sfondo del PDF-document usando valori RGB."
type: docs
url: /it/rust-cpp/organize/set_background/
---

_Imposta il colore di sfondo del PDF-document usando valori RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Imposta il colore di sfondo del PDF-document usando valori RGB
    pdf.set_background(200, 100, 101)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```