---
title: "get_meta_info"
second_title: "Aspose.PDF для Rust через C++"
description: "Получает значение метаинформации PDF-документа."
type: docs
url: /ru/rust-cpp/core/get_meta_info/
---

_Получает значение метаинформации PDF-документа._

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
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Получить значение метаинформации PDF-документа
    let author = pdf.get_meta_info("Author")?;

    // Вывести результат
    println!("Author: {}", author);

    Ok(())
}

```