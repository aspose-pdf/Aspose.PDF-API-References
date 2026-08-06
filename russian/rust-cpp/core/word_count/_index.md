---
title: "word_count"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает количество слов в PDF-документе."
type: docs
url: /ru/rust-cpp/core/word_count/
---

_Возвращает количество слов в PDF-документе._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Вернуть количество слов в PDF-документе
    let count = pdf.word_count()?;

    // Вывести количество слов
    println!("Word count: {}", count);

    Ok(())
}

```