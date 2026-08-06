---
title: "remove_tables"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF 文档中移除表格。"
type: docs
url: /zh/rust-cpp/organize/remove_tables/
---

_从 PDF 文档中移除表格._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // 从 PDF 文档中移除表格
    pdf.remove_tables()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```