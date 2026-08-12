---
title: "page_add_page_num"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет номер страницы на странице."
type: docs
url: /ru/rust-cpp/organize/page_add_page_num/
---

_Добавляет номер страницы на странице._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить номер страницы на страницу
    pdf.page_add_page_num(1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```