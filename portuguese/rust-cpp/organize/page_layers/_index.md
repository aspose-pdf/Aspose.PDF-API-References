---
title: "page_layers"
second_title: "Aspose.PDF para Rust via C++"
description: "Obtém os nomes das camadas na página."
type: docs
url: /pt/rust-cpp/organize/page_layers/
---

_Obtém os nomes das camadas na página._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample_layers.pdf")?;

    // Obtenha os nomes das camadas na página 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```