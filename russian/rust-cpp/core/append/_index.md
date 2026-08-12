---
title: "append"
second_title: "Aspose.PDF для Rust через C++"
description: "Добавляет страницы из другого PDF-document."
type: docs
url: /ru/rust-cpp/core/append/
---

_Добавляет страницы из другого PDF-document._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте основной PDF-document
    let pdf = Document::open("sample.pdf")?;

    // Открыть другой PDF-документ для добавления
    let another_pdf = Document::open("sample1page.pdf")?;

    // Добавить страницы из другого PDF-документа
    pdf.append(&another_pdf)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```