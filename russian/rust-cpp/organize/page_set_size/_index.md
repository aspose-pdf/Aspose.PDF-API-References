---
title: "page_set_size"
second_title: "Aspose.PDF для Rust через C++"
description: "Устанавливает размер страницы в PDF-document."
type: docs
url: /ru/rust-cpp/organize/page_set_size/
---

_Устанавливает размер страницы в PDF-document._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Установить размер страницы в PDF-document
    pdf.page_set_size(1, PageSize::A1)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```