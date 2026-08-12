---
title: "page_word_count"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 지정된 페이지에서 단어 수를 반환합니다."
type: docs
url: /ko/rust-cpp/core/page_word_count/
---

_PDF 문서의 지정된 페이지에서 단어 수를 반환합니다._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지 번호를 지정합니다 (1부터 시작하는 인덱스)
    let page_number = 1;

    // 지정된 페이지의 단어 수를 반환합니다
    let count = pdf.page_word_count(page_number)?;

    // 단어 수를 출력합니다
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```