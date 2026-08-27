---
title: "unembed_fonts"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中取消嵌入字体。"
type: docs
url: /zh/rust-cpp/organize/unembed_fonts/
---

_从 PDF-document 中取消嵌入字体._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // 取消嵌入 PDF-document 的字体
    pdf.unembed_fonts()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```