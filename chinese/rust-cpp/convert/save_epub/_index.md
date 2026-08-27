---
title: "save_epub"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 转换并保存为 EPUB-document。"
type: docs
url: /zh/rust-cpp/convert/save_epub/
---

_将先前打开的 PDF-document 转换并保存为 EPUB-document._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // 将先前打开的 PDF-document 转换并保存为 Epub-document
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```