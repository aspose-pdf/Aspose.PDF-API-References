---
title: "page_layers"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtiene los nombres de las capas en la página."
type: docs
url: /es/rust-cpp/organize/page_layers/
---

_Obtiene los nombres de las capas en la página._

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
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample_layers.pdf")?;

    // Obtén los nombres de las capas en la página 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```