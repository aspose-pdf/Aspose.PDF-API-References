---
title: "page_count"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает количество страниц в PDF-документе."
type: docs
url: /ru/rust-cpp/core/page_count/
---

_Возвращает количество страниц в PDF-документе._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // Вернуть количество страниц в PDF-документе
    let count = pdf.page_count()?;

    // Вывести количество страниц
    println!("Count: {}", count);

    Ok(())
}

```