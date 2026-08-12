---
title: "page_word_count"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает количество слов на указанной странице в PDF-документе."
type: docs
url: /ru/rust-cpp/core/page_word_count/
---

_Возвращает количество слов на указанной странице в PDF-документе._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
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

    // Вернуть количество слов на указанной странице
    let count = pdf.page_word_count(page_number)?;

    // Вывести количество слов
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```