---
title: "get_meta_info"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF 文档的元信息值。"
type: docs
url: /zh/rust-cpp/core/get_meta_info/
---

_获取 PDF 文档的元信息值。_

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 获取 PDF 文档的元信息值
    let author = pdf.get_meta_info("Author")?;

    // 打印结果
    println!("Author: {}", author);

    Ok(())
}

```