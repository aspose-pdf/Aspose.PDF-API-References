---
title: "open"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "파일 이름으로 PDF-document을 엽니다."
type: docs
url: /ko/rust-cpp/core/open/
---

_파일 이름으로 PDF-document을 엽니다._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```