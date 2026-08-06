---
title: "append_pages"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет выбранные страницы из другого PDF-документа."
type: docs
url: /ru/rust-cpp/core/append_pages/
---

_Добавляет выбранные страницы из другого PDF-документа._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте основной PDF-document
    let pdf = Document::open("sample1page.pdf")?;

    // Открыть другой PDF-документ для добавления
    let another_pdf = Document::open("sample.pdf")?;

    // Добавьте конкретные страницы (1 и 3) из другого PDF-документа
    pdf.append_pages(&another_pdf, "1,3")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```