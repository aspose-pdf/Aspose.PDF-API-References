---
title: "is_linearized"
second_title: "Aspose.PDF for Rust via C++"
description: "获取指示文档是否线性化的值。"
type: docs
url: /zh/rust-cpp/core/is_linearized/
---

_获取指示文档是否线性化的值。_

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 获取指示文档是否线性化的值
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```