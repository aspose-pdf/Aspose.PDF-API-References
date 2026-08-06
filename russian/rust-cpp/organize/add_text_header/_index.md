---
title: "add_text_header"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет текст в заголовок PDF-документа."
type: docs
url: /ru/rust-cpp/organize/add_text_header/
---

_Добавляет текст в заголовок PDF-документа._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить текст в заголовок PDF-документа
    pdf.add_text_header("HEADER")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```