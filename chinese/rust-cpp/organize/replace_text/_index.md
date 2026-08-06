---
title: "replace_text"
second_title: "Aspose.PDF for Rust via C++"
description: "替换文本。"
type: docs
url: /zh/rust-cpp/organize/replace_text/
---

_替换文本。_

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 替换 PDF-文档 中的文本
    pdf.replace_text("PDF", "TXT")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```