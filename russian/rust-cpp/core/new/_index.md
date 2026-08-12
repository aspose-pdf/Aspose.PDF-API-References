---
title: "new"
second_title: "Aspose.PDF для Rust через C++"
description: "Создаёт новый PDF-документ."
type: docs
url: /ru/rust-cpp/core/new/
---

_Создаёт новый PDF-документ._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Создайте новый PDF-документ
    let pdf = Document::new()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```