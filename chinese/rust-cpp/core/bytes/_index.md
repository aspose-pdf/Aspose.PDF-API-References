---
title: "bytes"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF-document 的内容，形式为字节向量。"
type: docs
url: /zh/rust-cpp/core/bytes/
---

_返回 PDF-document 的内容，形式为字节向量。_

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 创建一个新的 PDF-document
    let pdf = Document::new()?;

    // 返回 PDF-document 的内容，形式为字节向量
    let data = pdf.bytes()?;

    // 打印字节向量的长度
    println!("Length: {}", data.len());

    Ok(())
}

```