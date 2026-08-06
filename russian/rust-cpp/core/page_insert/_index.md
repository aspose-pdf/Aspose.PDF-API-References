---
title: "page_insert"
second_title: "Aspose.PDF для Rust через C++"
description: "Вставляет новую страницу в указанную позицию в PDF-document."
type: docs
url: /ru/rust-cpp/core/page_insert/
---

_Вставляет новую страницу в указанную позицию в PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // Вставьте новую страницу в указанную позицию в PDF-document
    pdf.page_insert(1)?;

    // Сохраните ранее открытый PDF-document
    pdf.save()?;

    Ok(())
}

```