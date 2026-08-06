---
title: "remove_hidden_text"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет скрытый текст из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_hidden_text/
---

_Удаляет скрытый текст из PDF-документа._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Удалить скрытый текст из PDF-документа
    pdf.remove_hidden_text()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```