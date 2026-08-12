---
title: "page_replace_font"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지의 글꼴을 교체합니다."
type: docs
url: /ko/rust-cpp/organize/page_replace_font/
---

_페이지의 글꼴을 교체합니다._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 페이지의 글꼴을 교체
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```