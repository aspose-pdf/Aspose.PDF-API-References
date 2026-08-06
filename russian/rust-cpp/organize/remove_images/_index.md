---
title: "remove_images"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет изображения из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_images/
---

_Удаляет изображения из PDF-документа._

```rust
pub fn remove_images(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Удалить изображения из PDF-документа
    pdf.remove_images()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_images.pdf")?;

    Ok(())
}

```