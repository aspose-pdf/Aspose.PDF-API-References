---
title: "page_is_blank"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document에서 페이지가 비어 있는지 반환합니다."
type: docs
url: /ko/rust-cpp/core/page_is_blank/
---

_PDF-document에서 페이지가 비어 있음을 반환합니다._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지 번호를 지정합니다 (1부터 시작하는 인덱스)
    let page_number = 1;

    // PDF-document에서 페이지가 비어 있음을 반환합니다
    let is_blank = pdf.page_is_blank(page_number)?;

    // 지정된 페이지가 비어 있으면 출력합니다
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```