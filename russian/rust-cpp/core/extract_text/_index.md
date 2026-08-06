---
title: "extract_text"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает содержимое PDF-документа в виде обычного текста."
type: docs
url: /ru/rust-cpp/core/extract_text/
---

_Возвращает содержимое PDF-документа в виде обычного текста._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Вернуть содержимое PDF-документа в виде обычного текста
    let txt = pdf.extract_text()?;

    // Вывести извлечённый текст
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```