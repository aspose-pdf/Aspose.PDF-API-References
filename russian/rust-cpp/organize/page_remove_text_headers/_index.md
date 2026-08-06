---
title: "page_remove_text_headers"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет текстовые заголовки на странице."
type: docs
url: /ru/rust-cpp/organize/page_remove_text_headers/
---

_Удаляет текстовые заголовки на странице._

```rust
pub fn page_remove_text_headers(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Удалить текстовые заголовки на странице
    pdf.page_remove_text_headers(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_remove_text_headers.pdf")?;

    Ok(())
}

```