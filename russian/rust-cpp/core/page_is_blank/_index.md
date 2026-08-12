---
title: "page_is_blank"
second_title: "Aspose.PDF для Rust через C++"
description: "Вернуть, является ли страница пустой в PDF-документе."
type: docs
url: /ru/rust-cpp/core/page_is_blank/
---

_Страница пустая в PDF-документе._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Укажите номер страницы (индекс, начиная с 1)
    let page_number = 1;

    // Страница пустая в PDF-документе
    let is_blank = pdf.page_is_blank(page_number)?;

    // Вывести, если указанная страница пустая
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```