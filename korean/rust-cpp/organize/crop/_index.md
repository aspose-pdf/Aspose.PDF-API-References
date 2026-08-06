---
title: "자르기"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 페이지를 자릅니다."
type: docs
url: /ko/rust-cpp/organize/crop/
---

_PDF-document의 페이지를 자릅니다._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document의 페이지를 자르기
    pdf.crop(10.5)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```