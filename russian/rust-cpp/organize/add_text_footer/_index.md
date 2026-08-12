---
title: "add_text_footer"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет текст в нижний колонтитул PDF-документа."
type: docs
url: /ru/rust-cpp/organize/add_text_footer/
---

_Добавляет текст в нижний колонтитул PDF-документа._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить текст в нижний колонтитул PDF-документа
    pdf.add_text_footer("FOOTER")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```