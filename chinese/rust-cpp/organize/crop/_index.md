---
title: "裁剪"
second_title: "Aspose.PDF for Rust via C++"
description: "裁剪 PDF-document 的页面。"
type: docs
url: /zh/rust-cpp/organize/crop/
---

_裁剪 PDF-document 的页面._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 裁剪 PDF-document 的页面
    pdf.crop(10.5)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```