---
title: "split_at"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "현재 PDF 문서를 두 개의 새 PDF 문서로 분할합니다."
type: docs
url: /ko/rust-cpp/core/split_at/
---

_현재 PDF 문서를 두 개의 새 PDF 문서로 분할합니다._

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
    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf_split = Document::open("sample.pdf")?;

    // 현재 PDF 문서를 두 개의 새 PDF 문서로 분할합니다
    let (left, right) = pdf_split.split_at(2)?;

    // 각 분할된 부분을 별개의 PDF-document로 저장합니다
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```