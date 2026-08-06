---
title: "extract_text"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document 내용을 일반 텍스트로 반환합니다."
type: docs
url: /ko/rust-cpp/core/extract_text/
---

_PDF-document 내용을 일반 텍스트로 반환합니다._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document 내용을 일반 텍스트로 반환합니다
    let txt = pdf.extract_text()?;

    // 추출된 텍스트를 출력합니다
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```