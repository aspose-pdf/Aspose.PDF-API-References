---
title: "save_as"
second_title: "Aspose.PDF для Rust через C++"
description: "Сохраняет ранее открытый PDF-документ с новым именем файла."
type: docs
url: /ru/rust-cpp/core/save_as/
---

_Сохраняет ранее открытый PDF-документ с новым именем файла._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
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
    // Создайте новый PDF-документ
    let pdf = Document::new()?;

    // Сохраните PDF-документ с новым именем файла
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```