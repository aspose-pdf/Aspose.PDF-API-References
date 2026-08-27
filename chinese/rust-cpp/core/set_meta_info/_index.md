---
title: "set_meta_info"
second_title: "Aspose.PDF for Rust via C++"
description: "设置 PDF 文档的元信息值。"
type: docs
url: /zh/rust-cpp/core/set_meta_info/
---

_设置 PDF 文档的元信息值。_

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 设置 PDF 文档的元信息值
    pdf.set_meta_info("Author", "Aspose")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```