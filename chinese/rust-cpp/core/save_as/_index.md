---
title: "save_as"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 另存为新文件名。"
type: docs
url: /zh/rust-cpp/core/save_as/
---

_将先前打开的 PDF-document 另存为新文件名._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
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
    // 创建一个新的 PDF-document
    let pdf = Document::new()?;

    // 将 PDF-document 保存为新文件名
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```