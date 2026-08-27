---
title: "embed_fonts"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF-document 中嵌入字体。"
type: docs
url: /zh/rust-cpp/organize/embed_fonts/
---

_在 PDF-document 中嵌入字体._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // 在 PDF-document 中嵌入字体
    pdf.embed_fonts()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```