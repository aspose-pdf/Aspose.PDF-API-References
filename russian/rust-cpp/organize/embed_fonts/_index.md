---
title: "embed_fonts"
second_title: "Aspose.PDF для Rust через C++"
description: "Встраивает шрифты в PDF-документ."
type: docs
url: /ru/rust-cpp/organize/embed_fonts/
---

_Встраивает шрифты в PDF-документ._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // Встроить шрифты в PDF-документ
    pdf.embed_fonts()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```