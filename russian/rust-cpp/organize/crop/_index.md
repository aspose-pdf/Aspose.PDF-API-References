---
title: "обрезать"
second_title: "Aspose.PDF для Rust через C++"
description: "Обрезает страницы PDF-document."
type: docs
url: /ru/rust-cpp/organize/crop/
---

_Обрезает страницы PDF-document._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Обрезать страницы PDF-document
    pdf.crop(10.5)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```