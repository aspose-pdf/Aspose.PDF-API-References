---
title: "remove_text_headers"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет текстовые заголовки из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_text_headers/
---

_Удаляет текстовые заголовки из PDF-документа._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Удалить текстовые заголовки из PDF-документа
    pdf.remove_text_headers()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```