---
title: "page_layers"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki katmanların adlarını alır."
type: docs
url: /tr/rust-cpp/organize/page_layers/
---

_Sayfadaki katmanların adlarını alır._

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
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample_layers.pdf")?;

    // Sayfa 1'deki katmanların adlarını al
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```