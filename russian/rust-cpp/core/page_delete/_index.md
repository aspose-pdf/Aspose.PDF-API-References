---
title: "page_delete"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет указанную страницу из PDF-документа."
type: docs
url: /ru/rust-cpp/core/page_delete/
---

_Удаляет указанную страницу из PDF-документа._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // Удалить указанную страницу в PDF-документе
    pdf.page_delete(1)?;

    // Сохраните ранее открытый PDF-document
    pdf.save()?;

    Ok(())
}

```