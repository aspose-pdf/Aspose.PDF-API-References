---
title: "unembed_fonts"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет шрифты из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/unembed_fonts/
---

_Удаляет шрифты из PDF-документа._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Удалить шрифты из PDF-документа
    pdf.unembed_fonts()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```