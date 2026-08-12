---
title: "split_at"
second_title: "Aspose.PDF для Rust через C++"
description: "Разделяет текущий PDF-документ на два новых PDF-документа."
type: docs
url: /ru/rust-cpp/core/split_at/
---

_Разделяет текущий PDF-документ на два новых PDF-документа._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document с именем "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Разделить текущий PDF-документ на два новых PDF-документа
    let (left, right) = pdf_split.split_at(2)?;

    // Сохраните каждую часть после разделения как отдельный PDF-document
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```