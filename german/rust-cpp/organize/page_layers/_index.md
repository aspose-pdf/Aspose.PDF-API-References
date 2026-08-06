---
title: "page_layers"
second_title: "Aspose.PDF für Rust über C++"
description: "Ermittelt die Namen der Ebenen auf der Seite."
type: docs
url: /de/rust-cpp/organize/page_layers/
---

_Ermittelt die Namen der Ebenen auf der Seite._

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
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample_layers.pdf")?;

    // Erhalte die Namen der Ebenen auf Seite 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```