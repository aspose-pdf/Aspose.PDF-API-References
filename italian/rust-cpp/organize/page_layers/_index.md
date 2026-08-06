---
title: "page_layers"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottiene i nomi dei livelli nella pagina."
type: docs
url: /it/rust-cpp/organize/page_layers/
---

_Ottiene i nomi dei livelli nella pagina._

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
    // Apri un PDF-document da file
    let pdf = Document::open("sample_layers.pdf")?;

    // Ottieni i nomi dei livelli nella pagina 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```