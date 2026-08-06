---
title: "remove_watermarks"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除水印。"
type: docs
url: /zh/rust-cpp/organize/remove_watermarks/
---

_从 PDF-document 中移除水印。_

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // 从 PDF-document 中移除水印
    pdf.remove_watermarks()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```