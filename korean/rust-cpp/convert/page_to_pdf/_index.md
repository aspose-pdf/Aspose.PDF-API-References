---
title: "page_to_pdf"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "지정된 페이지를 PDF-document로 변환하고 저장합니다."
type: docs
url: /ko/rust-cpp/convert/page_to_pdf/
---

_지정된 페이지를 PDF-document로 변환하고 저장합니다._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // 지정된 페이지를 PDF-document로 변환하고 저장합니다
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```