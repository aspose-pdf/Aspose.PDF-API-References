---
title: "page_replace_font"
second_title: "Aspose.PDF для Rust через C++"
description: "Заменяет шрифт на странице."
type: docs
url: /ru/rust-cpp/organize/page_replace_font/
---

_Заменяет шрифт на странице._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Заменить шрифт на странице
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```