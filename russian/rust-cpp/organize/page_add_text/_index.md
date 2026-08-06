---
title: "page_add_text"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет текст на страницу."
type: docs
url: /ru/rust-cpp/organize/page_add_text/
---

_Добавляет текст на страницу._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить текст на страницу
    pdf.page_add_text(1, "added text")?;

    // Сохраните ранее открытый PDF-document
    pdf.save()?;

    Ok(())
}

```