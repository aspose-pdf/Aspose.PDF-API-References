---
title: "split_at_page"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقسم مستند PDF-document إلى مستندين PDF-documents جديدين."
type: docs
url: /ar/rust-cpp/core/split_at_page/
---

_يقسم مستند PDF-document إلى مستندين PDF-documents جديدين._

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
    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // قسم مستند PDF-document إلى مستندين PDF-documents جديدين
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // احفظ كل جزء مقسّم كملف PDF-document منفصل
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```