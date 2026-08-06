---
title: "split_at_page"
second_title: "Aspose.PDF for Rust via C++"
description: "将 PDF-document 拆分为两个新的 PDF-documents."
type: docs
url: /zh/rust-cpp/core/split_at_page/
---

_将 PDF-document 拆分为两个新的 PDF-documents._

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
    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf_split = Document::open("sample.pdf")?;

    // 将 PDF-document 拆分为两个新的 PDF-documents
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // 将每个拆分部分保存为单独的 PDF-document
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```