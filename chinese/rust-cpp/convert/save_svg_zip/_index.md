---
title: "save_svg_zip"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 转换并保存为 SVG-archive。"
type: docs
url: /zh/rust-cpp/convert/save_svg_zip/
---

_将先前打开的 PDF-document 转换并保存为 SVG-archive。_

```rust
pub fn save_svg_zip(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 转换并保存先前打开的 PDF-document 为 SVG-archive
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```