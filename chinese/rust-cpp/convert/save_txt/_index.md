---
title: "save_txt"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 转换并保存为 TXT-document。"
type: docs
url: /zh/rust-cpp/convert/save_txt/
---

_将先前打开的 PDF-document 转换并保存为 TXT-document。_

```rust
pub fn save_txt(&self, filename: &str) -> Result<(), PdfError>
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

    // 转换并保存先前打开的 PDF-document 为 Txt-document
    pdf.save_txt("sample.txt")?;

    Ok(())
}

```