---
title: "append"
second_title: "Aspose.PDF for Rust via C++"
description: "追加来自另一个 PDF-document 的页面."
type: docs
url: /zh/rust-cpp/core/append/
---

_追加来自另一个 PDF-document 的页面._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开主要的 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 打开另一个 PDF 文档以追加
    let another_pdf = Document::open("sample1page.pdf")?;

    // 追加来自另一个 PDF 文档的页面
    pdf.append(&another_pdf)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```