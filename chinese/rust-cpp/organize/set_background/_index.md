---
title: "set_background"
second_title: "Aspose.PDF for Rust via C++"
description: "使用 RGB 值设置 PDF 文档的背景颜色。"
type: docs
url: /zh/rust-cpp/organize/set_background/
---

_使用 RGB 值设置 PDF 文档的背景颜色。_

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 使用 RGB 值设置 PDF 文档的背景颜色
    pdf.set_background(200, 100, 101)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```