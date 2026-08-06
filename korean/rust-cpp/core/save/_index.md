---
title: "save"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열었던 PDF 문서를 저장합니다."
type: docs
url: /ko/rust-cpp/core/save/
---

_이전에 열었던 PDF 문서를 저장합니다._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이전에 열었던 PDF-document를 저장합니다
    pdf.save()?;

    Ok(())
}

```