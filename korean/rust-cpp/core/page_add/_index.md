---
title: "page_add"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서에 새 페이지를 추가합니다."
type: docs
url: /ko/rust-cpp/core/page_add/
---

_PDF 문서에 새 페이지를 추가합니다._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서에 새 페이지를 추가
    pdf.page_add()?;

    // 이전에 열었던 PDF-document를 저장합니다
    pdf.save()?;

    Ok(())
}

```