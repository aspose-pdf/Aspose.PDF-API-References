---
title: "repair"
second_title: "Aspose.PDF for Rust via C++"
description: "修复 PDF 文档。"
type: docs
url: /zh/rust-cpp/organize/repair/
---

_修复 PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // 修复 PDF-document
    pdf.repair()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```