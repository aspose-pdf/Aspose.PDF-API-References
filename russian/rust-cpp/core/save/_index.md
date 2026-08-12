---
title: "save"
second_title: "Aspose.PDF для Rust через C++"
description: "Сохраняет ранее открытый PDF-документ."
type: docs
url: /ru/rust-cpp/core/save/
---

_Сохраняет ранее открытый PDF-документ._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document с именем "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Сохраните ранее открытый PDF-document
    pdf.save()?;

    Ok(())
}

```