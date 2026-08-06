---
title: "append_pages"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "다른 PDF 문서에서 선택한 페이지를 추가합니다."
type: docs
url: /ko/rust-cpp/core/append_pages/
---

_다른 PDF 문서에서 선택한 페이지를 추가합니다._

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
    // 주요 PDF-document를 엽니다
    let pdf = Document::open("sample1page.pdf")?;

    // 다른 PDF-document을 추가하기 위해 엽니다
    let another_pdf = Document::open("sample.pdf")?;

    // 다른 PDF 문서에서 특정 페이지(1 및 3)를 추가합니다
    pdf.append_pages(&another_pdf, "1,3")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```