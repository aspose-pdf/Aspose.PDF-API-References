---
title: "save_booklet"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 转换并保存为小册子 PDF-document。"
type: docs
url: /zh/rust-cpp/convert/save_booklet/
---

_将先前打开的 PDF-document 转换并保存为小册子 PDF-document._

```rust
pub fn save_booklet(&self, filename: &str) -> Result<(), PdfError>
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

    // 将先前打开的 PDF-document 转换并保存为小册子 PDF-document
    pdf.save_booklet("sample_booklet.pdf")?;

    Ok(())
}
```