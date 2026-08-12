---
title: "append"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "다른 PDF-document의 페이지를 추가합니다."
type: docs
url: /ko/rust-cpp/core/append/
---

_다른 PDF-document의 페이지를 추가합니다._

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
    // 주요 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 다른 PDF-document을 추가하기 위해 엽니다
    let another_pdf = Document::open("sample1page.pdf")?;

    // 다른 PDF-document에서 페이지를 추가합니다
    pdf.append(&another_pdf)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```