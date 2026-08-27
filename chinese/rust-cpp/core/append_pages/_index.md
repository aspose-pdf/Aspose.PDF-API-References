---
title: "append_pages"
second_title: "Aspose.PDF for Rust via C++"
description: "从另一个 PDF 文档追加选定的页面。"
type: docs
url: /zh/rust-cpp/core/append_pages/
---

_从另一个 PDF 文档追加选定的页面。_

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开主要的 PDF-document
    let pdf = Document::open("sample1page.pdf")?;

    // 打开另一个 PDF 文档以追加
    let another_pdf = Document::open("sample.pdf")?;

    // 从另一个 PDF 文档追加特定页面（1 和 3）
    pdf.append_pages(&another_pdf, "1,3")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```