---
title: "validate"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 형식 준수를 위해 PDF 문서를 검증합니다."
type: docs
url: /ko/rust-cpp/organize/validate/
---

_PDF 형식 준수를 위해 PDF 문서를 검증합니다._

```rust
    pub fn validate(
        &self,
        pdf_format: PdfFormat,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the validation log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document가 PDF 형식에 준수하는지 검증합니다
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // 검증 결과와 전체 로그를 출력합니다
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```