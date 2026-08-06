---
title: "add_text_header"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF 文档的页眉中添加文本。"
type: docs
url: /zh/rust-cpp/organize/add_text_header/
---

_在 PDF 文档的页眉中添加文本。_

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在 PDF-文档 的页眉中添加文本
    pdf.add_text_header("HEADER")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```