---
title: "open"
second_title: "Aspose.PDF for Rust via C++"
description: "使用文件名打开 PDF 文档。"
type: docs
url: /zh/rust-cpp/core/open/
---

_使用文件名打开 PDF 文档。_

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```