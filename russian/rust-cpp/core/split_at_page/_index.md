---
title: "split_at_page"
second_title: "Aspose.PDF для Rust через C++"
description: "Разделяет PDF-document на два новых PDF-documents."
type: docs
url: /ru/rust-cpp/core/split_at_page/
---

_Разделяет PDF-document на два новых PDF-documents._

```rust
pub fn split_at_page(document: &Document, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
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

    // Разделите PDF-document на два новых PDF-documents
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // Сохраните каждую часть после разделения как отдельный PDF-document
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```