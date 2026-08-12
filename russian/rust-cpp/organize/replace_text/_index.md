---
title: "replace_text"
second_title: "Aspose.PDF для Rust через C++"
description: "Заменяет текст."
type: docs
url: /ru/rust-cpp/organize/replace_text/
---

_Заменяет текст._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Заменить текст в PDF-документе
    pdf.replace_text("PDF", "TXT")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```