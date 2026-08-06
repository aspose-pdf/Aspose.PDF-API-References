---
title: "optimize_resource"
second_title: "Aspose.PDF for Rust via C++"
description: "优化 PDF-document 的资源。"
type: docs
url: /zh/rust-cpp/organize/optimize_resource/
---

_优化 PDF-document 的资源._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // 优化 PDF-document 的资源
    pdf.optimize_resource()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```