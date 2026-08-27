---
title: "remove_hidden_text"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除隐藏文本。"
type: docs
url: /zh/rust-cpp/organize/remove_hidden_text/
---

_从 PDF-document 中移除隐藏文本。_

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // 删除 PDF-文档 中的隐藏文本
    pdf.remove_hidden_text()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```