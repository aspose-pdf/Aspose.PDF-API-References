---
title: "save_docx_enhanced"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열어둔 PDF 문서를 Enhanced Recognition Mode(완전 편집 가능한 표와 단락)를 사용한 DOCX 문서로 변환하고 저장합니다."
type: docs
url: /ko/rust-cpp/convert/save_docx_enhanced/
---

_이전에 열어둔 PDF 문서를 Enhanced Recognition Mode(완전 편집 가능한 표와 단락)를 사용한 DOCX 문서로 변환하고 저장합니다._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이전에 열어둔 PDF 문서를 Enhanced Recognition Mode(완전 편집 가능한 표와 단락)를 사용한 DOCX 문서로 변환하고 저장합니다
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```