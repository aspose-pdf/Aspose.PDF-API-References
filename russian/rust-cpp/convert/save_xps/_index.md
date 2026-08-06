---
title: "save_xps"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует и сохраняет ранее открытый PDF-документ как XPS-документ."
type: docs
url: /ru/rust-cpp/convert/save_xps/
---

_Преобразует и сохраняет ранее открытый PDF-документ как XPS-документ._

```rust
pub fn save_xps(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Преобразовать и сохранить ранее открытый PDF-документ как Xps-документ
    pdf.save_xps("sample.xps")?;

    Ok(())
}

```