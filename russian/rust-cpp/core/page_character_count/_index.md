---
title: "page_character_count"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает количество символов на указанной странице в PDF-документе."
type: docs
url: /ru/rust-cpp/core/page_character_count/
---

_Возвращает количество символов на указанной странице в PDF-документе._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Укажите номер страницы (индекс, начиная с 1)
    let page_number = 1;

    // Вернуть количество символов на указанной странице
    let count = pdf.page_character_count(page_number)?;

    // Вывести количество символов
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```