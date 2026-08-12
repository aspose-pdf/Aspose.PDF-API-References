---
title: "add_text_header"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 헤더에 텍스트를 추가합니다."
type: docs
url: /ko/rust-cpp/organize/add_text_header/
---

_PDF 문서의 헤더에 텍스트를 추가합니다._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // PDF 문서 헤더에 텍스트를 추가합니다
    pdf.add_text_header("HEADER")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```