---
title: "is_linearized"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다."
type: docs
url: /ko/rust-cpp/core/is_linearized/
---

_문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```