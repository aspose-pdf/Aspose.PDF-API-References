---
title: "embed_fonts"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서에 글꼴을 포함합니다."
type: docs
url: /ko/rust-cpp/organize/embed_fonts/
---

_PDF 문서에 글꼴을 포함합니다._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서에 글꼴 포함
    pdf.embed_fonts()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```