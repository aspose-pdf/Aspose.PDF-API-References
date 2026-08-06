---
title: "page_remove_text_footers"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет текстовые нижние колонтитулы на странице."
type: docs
url: /ru/rust-cpp/organize/page_remove_text_footers/
---

_Удаляет текстовые нижние колонтитулы на странице._

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
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

    // Удалить текстовые нижние колонтитулы на странице
    pdf.page_remove_text_footers(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```