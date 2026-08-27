---
title: "clear_meta_info"
second_title: "Aspose.PDF for Rust via C++"
description: "清除 PDF 文档的所有元信息值。"
type: docs
url: /zh/rust-cpp/core/clear_meta_info/
---

_清除 PDF 文档的所有元信息值。_

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // 清除 PDF 文档的所有元信息值
    pdf.clear_meta_info()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```