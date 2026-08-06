---
title: "remove_javascripts"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除 Java 脚本."
type: docs
url: /zh/rust-cpp/organize/remove_javascripts/
---

_从 PDF-document 中移除 Java 脚本._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // 删除 PDF-文档 中的 Java 脚本
    pdf.remove_javascripts()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```