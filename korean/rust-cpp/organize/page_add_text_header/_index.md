---
title: "page_add_text_header"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지 헤더에 텍스트를 추가합니다."
type: docs
url: /ko/rust-cpp/organize/page_add_text_header/
---

_페이지 헤더에 텍스트를 추가합니다._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지 머리글에 텍스트를 추가합니다
    pdf.page_add_text_header(1, "HEADER")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```