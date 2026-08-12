---
title: "page_replace_text"
second_title: "Aspose.PDF для Rust через C++"
description: "Заменяет текст на странице."
type: docs
url: /ru/rust-cpp/organize/page_replace_text/
---

_Заменяет текст на странице._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Заменить текст на странице
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```