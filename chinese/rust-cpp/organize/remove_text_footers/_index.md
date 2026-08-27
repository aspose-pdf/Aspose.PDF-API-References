---
title: "remove_text_footers"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除文本页脚."
type: docs
url: /zh/rust-cpp/organize/remove_text_footers/
---

_从 PDF-document 中移除文本页脚._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // 移除 PDF-document 中的文本页脚
    pdf.remove_text_footers()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```