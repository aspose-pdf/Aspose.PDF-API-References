---
title: "page_layers"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mendapatkan nama lapisan pada halaman."
type: docs
url: /id/rust-cpp/organize/page_layers/
---

_Mendapatkan nama lapisan pada halaman._

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
    // Buka PDF-document dari file
    let pdf = Document::open("sample_layers.pdf")?;

    // Dapatkan nama lapisan pada halaman 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```