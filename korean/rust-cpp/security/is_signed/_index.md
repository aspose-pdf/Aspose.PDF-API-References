---
title: "is_signed"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 서명 상태를 가져옵니다."
type: docs
url: /ko/rust-cpp/security/is_signed/
---

_PDF-document의 서명 상태를 가져옵니다._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample_with_sign.pdf"라는 PDF 문서를 엽니다
    let pdf = Document::open("sample_with_sign.pdf")?;

    // PDF-document의 서명 상태를 가져옵니다
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```