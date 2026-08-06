---
title: "page_layers"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحصل على أسماء الطبقات في الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_layers/
---

_يحصل على أسماء الطبقات في الصفحة._

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
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample_layers.pdf")?;

    // احصل على أسماء الطبقات في الصفحة 1
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```