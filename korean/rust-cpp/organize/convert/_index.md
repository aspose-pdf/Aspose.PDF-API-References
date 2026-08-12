---
title: "convert"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "지정된 PDF 형식으로 PDF-document를 PDF-document로 변환합니다."
type: docs
url: /ko/rust-cpp/organize/convert/
---

_지정된 PDF 형식으로 PDF-document를 PDF-document로 변환합니다._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document를 지정된 PDF 형식의 PDF-document로 변환합니다
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // 변환 결과와 전체 로그를 출력합니다
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```