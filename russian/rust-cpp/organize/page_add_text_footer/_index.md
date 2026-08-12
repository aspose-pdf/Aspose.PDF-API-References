---
title: "page_add_text_footer"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет текст в нижний колонтитул страницы."
type: docs
url: /ru/rust-cpp/organize/page_add_text_footer/
---

_Добавляет текст в нижний колонтитул страницы._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Добавить текст в нижний колонтитул страницы.
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```