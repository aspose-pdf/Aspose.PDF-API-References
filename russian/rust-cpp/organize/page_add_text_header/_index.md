---
title: "page_add_text_header"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет текст в заголовок страницы."
type: docs
url: /ru/rust-cpp/organize/page_add_text_header/
---

_Добавляет текст в заголовок страницы._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Добавить текст в заголовок страницы.
    pdf.page_add_text_header(1, "HEADER")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```