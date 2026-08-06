---
title: "remove_blank_pages"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中删除空白页。"
type: docs
url: /zh/rust-cpp/organize/remove_blank_pages/
---

_从 PDF-document 中删除空白页._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 删除 PDF-文档 中的空白页
    pdf.remove_blank_pages()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```