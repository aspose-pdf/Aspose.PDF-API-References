---
title: "page_layers"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämtar lagrens namn på sidan."
type: docs
url: /sv/rust-cpp/organize/page_layers/
---

_Hämtar lagrens namn på sidan._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample_layers.pdf")?;

    // Hämta namnen på lagren på sida 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```