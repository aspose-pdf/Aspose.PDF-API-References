---
title: "character_count"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF-document 中的字符计数。"
type: docs
url: /zh/rust-cpp/core/character_count/
---

_返回 PDF-document 中的字符计数。_

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 返回 PDF-document 中的字符计数
    let count = pdf.character_count()?;

    // 打印字符计数
    println!("Character count: {}", count);

    Ok(())
}

```