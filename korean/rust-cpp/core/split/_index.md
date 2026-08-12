---
title: "split"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다."
type: docs
url: /ko/rust-cpp/core/split/
---

_현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf_split = Document::open("sample.pdf")?;

    // 현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // 각 분할된 부분을 별개의 PDF-document로 저장합니다
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```