---
title: "character_count"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает количество символов в PDF-документе."
type: docs
url: /ru/rust-cpp/core/character_count/
---

_Возвращает количество символов в PDF-документе._

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
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Вернуть количество символов в PDF-документе
    let count = pdf.character_count()?;

    // Вывести количество символов
    println!("Character count: {}", count);

    Ok(())
}

```