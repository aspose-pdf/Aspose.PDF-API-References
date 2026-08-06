---
title: "grayscale"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document을 흑백으로 변환합니다."
type: docs
url: /ko/rust-cpp/organize/grayscale/
---

_PDF-document을 흑백으로 변환합니다._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // PDF-document을 흑백으로 변환
    pdf.grayscale()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```