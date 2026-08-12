---
title: "replace_font"
second_title: "Aspose.PDF для Rust через C++"
description: "Заменяет шрифт в PDF-документе."
type: docs
url: /ru/rust-cpp/organize/replace_font/
---

_Заменяет шрифт в PDF-документе._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Заменить шрифт в PDF-документе.
    pdf.replace_font("Helvetica", "Courier")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```