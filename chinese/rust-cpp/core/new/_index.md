---
title: "new"
second_title: "Aspose.PDF for Rust via C++"
description: "创建一个新的 PDF-document。"
type: docs
url: /zh/rust-cpp/core/new/
---

_创建一个新的 PDF-document._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 创建一个新的 PDF-document
    let pdf = Document::new()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```