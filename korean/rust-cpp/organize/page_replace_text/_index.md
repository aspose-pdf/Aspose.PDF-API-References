---
title: "page_replace_text"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지의 텍스트를 교체합니다."
type: docs
url: /ko/rust-cpp/organize/page_replace_text/
---

_페이지의 텍스트를 교체합니다._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지의 텍스트를 교체합니다
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```