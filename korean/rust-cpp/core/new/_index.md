---
title: "새"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "새 PDF 문서를 생성합니다."
type: docs
url: /ko/rust-cpp/core/new/
---

_새 PDF 문서를 생성합니다._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```