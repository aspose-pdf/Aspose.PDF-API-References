---
title: "merge_documents"
second_title: "Aspose.PDF for Rust via C++"
description: "通过合并提供的 PDF 文档来创建一个新 PDF 文档。"
type: docs
url: /zh/rust-cpp/core/merge_documents/
---

_通过合并提供的 PDF 文档来创建一个新 PDF 文档。_

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
    // 创建一个新的 PDF-document
    let pdf1 = Document::new()?;

    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf2 = Document::open("sample.pdf")?;

    // 通过合并提供的 PDF 文档来创建一个新 PDF 文档
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```