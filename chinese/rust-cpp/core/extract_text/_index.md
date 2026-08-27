---
title: "extract_text"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF 文档的内容为纯文本。"
type: docs
url: /zh/rust-cpp/core/extract_text/
---

_返回 PDF 文档的内容为纯文本。_

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 返回 PDF 文档的内容为纯文本
    let txt = pdf.extract_text()?;

    // 打印提取的文本
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```