---
title: "page_layers"
second_title: "Aspose.PDF for Rust via C++"
description: "获取页面上图层的名称。"
type: docs
url: /zh/rust-cpp/organize/page_layers/
---

_获取页面上图层的名称。_

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
    // 从文件打开 PDF-document
    let pdf = Document::open("sample_layers.pdf")?;

    // 获取第 1 页上图层的名称
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```