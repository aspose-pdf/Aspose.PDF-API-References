---
title: "page_set_size"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서에서 페이지의 크기를 설정합니다."
type: docs
url: /ko/rust-cpp/organize/page_set_size/
---

_PDF 문서에서 페이지의 크기를 설정합니다._

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
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서에서 페이지의 크기를 설정합니다
    pdf.page_set_size(1, PageSize::A1)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```