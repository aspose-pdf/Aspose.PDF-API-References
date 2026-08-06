---
title: "page_layers"
second_title: "Aspose.PDF для Rust через C++"
description: "Получает имена слоёв на странице."
type: docs
url: /ru/rust-cpp/organize/page_layers/
---

_Получает имена слоёв на странице._

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
    // Откройте PDF-document из файла
    let pdf = Document::open("sample_layers.pdf")?;

    // Получить имена слоёв на странице 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```