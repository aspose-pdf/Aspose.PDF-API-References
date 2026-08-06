---
title: "split_document"
second_title: "Aspose.PDF for Rust via C++"
description: "通过从源 PDF-document 中提取页面来创建多个新的 PDF-documents."
type: docs
url: /zh/rust-cpp/core/split_document/
---

_通过从源 PDF-document 中提取页面来创建多个新的 PDF-documents._

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
    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf_split = Document::open("sample.pdf")?;

    // 通过从源 PDF-document 中提取页面来创建多个新的 PDF-documents
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // 将每个拆分部分保存为单独的 PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```