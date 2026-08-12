---
title: "page_add_text"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지에 텍스트를 추가합니다."
type: docs
url: /ko/rust-cpp/organize/page_add_text/
---

_페이지에 텍스트를 추가합니다._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지에 텍스트를 추가합니다
    pdf.page_add_text(1, "added text")?;

    // 이전에 열었던 PDF-document를 저장합니다
    pdf.save()?;

    Ok(())
}

```