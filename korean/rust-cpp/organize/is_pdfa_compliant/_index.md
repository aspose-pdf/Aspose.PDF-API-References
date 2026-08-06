---
title: "is_pdfa_compliant"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document가 PDF/A 준수인지 확인합니다."
type: docs
url: /ko/rust-cpp/organize/is_pdfa_compliant/
---

_PDF-document가 PDF/A 준수인지 확인합니다._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
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

    // PDF-document의 PDF/A 준수 상태를 가져오기
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```