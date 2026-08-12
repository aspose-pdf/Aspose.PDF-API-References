---
title: "replace_font"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 글꼴을 교체합니다."
type: docs
url: /ko/rust-cpp/organize/replace_font/
---

_PDF 문서의 글꼴을 교체합니다._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // PDF-document의 글꼴을 교체합니다.
    pdf.replace_font("Helvetica", "Courier")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```