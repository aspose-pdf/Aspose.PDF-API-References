---
title: "page_count"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 페이지 수를 반환합니다."
type: docs
url: /ko/rust-cpp/core/page_count/
---

_PDF 문서의 페이지 수를 반환합니다._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서의 페이지 수를 반환합니다
    let count = pdf.page_count()?;

    // 페이지 수를 출력합니다
    println!("Count: {}", count);

    Ok(())
}

```