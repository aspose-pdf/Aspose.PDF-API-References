---
title: "add_page_num"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет номер страницы в PDF-документ."
type: docs
url: /ru/rust-cpp/organize/add_page_num/
---

_Добавляет номер страницы в PDF-документ._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // Добавить номер страницы в PDF-документ
    pdf.add_page_num()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```