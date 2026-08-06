---
title: "merge_documents"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다."
type: docs
url: /ko/rust-cpp/core/merge_documents/
---

_제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf1 = Document::new()?;

    // "sample.pdf"라는 PDF-document를 엽니다
    let pdf2 = Document::open("sample.pdf")?;

    // 제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```