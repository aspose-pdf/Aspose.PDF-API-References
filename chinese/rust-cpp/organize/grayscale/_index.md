---
title: "grayscale"
second_title: "Aspose.PDF for Rust via C++"
description: "将 PDF 文档转换为黑白。"
type: docs
url: /zh/rust-cpp/organize/grayscale/
---

_将 PDF 文档转换为黑白。_

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // 将 PDF 文档转换为黑白
    pdf.grayscale()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```