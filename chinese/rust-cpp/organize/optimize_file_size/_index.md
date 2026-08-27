---
title: "optimize_file_size"
second_title: "Aspose.PDF for Rust via C++"
description: "通过图像压缩质量优化 PDF 文档的大小。"
type: docs
url: /zh/rust-cpp/organize/optimize_file_size/
---

_通过图像压缩质量优化 PDF 文档的大小。_

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 优化 PDF 文档的大小，使用图像压缩质量
    pdf.optimize_file_size(50)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```