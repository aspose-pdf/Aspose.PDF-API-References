---
title: "bytes"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает содержимое PDF-документа в виде вектора байтов."
type: docs
url: /ru/rust-cpp/core/bytes/
---

_Возвращает содержимое PDF-документа в виде вектора байтов._

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
    // Создайте новый PDF-документ
    let pdf = Document::new()?;

    // Вернуть содержимое PDF-документа в виде вектора байтов
    let data = pdf.bytes()?;

    // Вывести длину вектора байтов
    println!("Length: {}", data.len());

    Ok(())
}

```