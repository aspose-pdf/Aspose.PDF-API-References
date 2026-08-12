---
title: "page_remove_text_footers"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지의 텍스트 바닥글을 제거합니다."
type: docs
url: /ko/rust-cpp/organize/page_remove_text_footers/
---

_페이지의 텍스트 바닥글을 제거합니다._

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지의 텍스트 바닥글을 제거합니다
    pdf.page_remove_text_footers(1)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```