---
title: "split_document"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "원본 PDF-document에서 페이지를 추출하여 여러 개의 새로운 PDF-documents를 생성합니다."
type: docs
url: /ko/rust-cpp/core/split_document/
---

_원본 PDF-document에서 페이지를 추출하여 여러 개의 새로운 PDF-documents를 생성합니다._

```rust
pub fn split_document(document: &Document, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
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

    // 원본 PDF-document에서 페이지를 추출하여 여러 개의 새로운 PDF-documents를 생성합니다
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // 각 분할된 부분을 별개의 PDF-document로 저장합니다
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```