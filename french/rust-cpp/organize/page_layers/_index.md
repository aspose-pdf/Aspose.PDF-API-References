---
title: "page_layers"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtient les noms des calques sur la page."
type: docs
url: /fr/rust-cpp/organize/page_layers/
---

_Obtient les noms des calques sur la page._

```rust
pub fn page_layers(&self, num: i32) -> Result<Vec<String>, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(Vec\<String\>)** - the array layers' names
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample_layers.pdf")?;

    // Obtenez les noms des calques sur la page 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```