---
title: "split_at_page"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document를 두 개의 새로운 PDF-documents로 분할합니다."
type: docs
url: /ko/rust-cpp/core/split_at_page/
---

_PDF-document를 두 개의 새로운 PDF-documents로 분할합니다._

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
    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf_split = Document::open("sample.pdf")?;

    // PDF-document를 두 개의 새로운 PDF-documents로 분할합니다
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // 각 분할된 부분을 별개의 PDF-document로 저장합니다
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```