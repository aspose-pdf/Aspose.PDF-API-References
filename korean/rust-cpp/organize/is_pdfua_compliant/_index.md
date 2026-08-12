---
title: "is_pdfua_compliant"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서가 PDF/UA 규격을 준수하는지 가져옵니다."
type: docs
url: /ko/rust-cpp/organize/is_pdfua_compliant/
---

_PDF 문서가 PDF/UA 규격을 준수하는지 가져옵니다._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // PDF 문서의 PDF/UA 준수 상태를 가져옵니다
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```