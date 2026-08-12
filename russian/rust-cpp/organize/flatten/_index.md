---
title: "flatten"
second_title: "Aspose.PDF для Rust через C++"
description: "Уплощает PDF-документ."
type: docs
url: /ru/rust-cpp/organize/flatten/
---

_Уплощает PDF-документ._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
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