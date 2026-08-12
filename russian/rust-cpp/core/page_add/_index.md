---
title: "page_add"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет новую страницу в PDF-документ."
type: docs
url: /ru/rust-cpp/core/page_add/
---

_Добавляет новую страницу в PDF-документ._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Добавить новую страницу в PDF-документ
    pdf.page_add()?;

    // Сохраните ранее открытый PDF-document
    pdf.save()?;

    Ok(())
}

```