---
title: "set_meta_info"
second_title: "Aspose.PDF для Rust через C++"
description: "Устанавливает значение метаданных PDF-документа."
type: docs
url: /ru/rust-cpp/core/set_meta_info/
---

_Устанавливает значение метаданных PDF-документа._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Установить значение метаданных PDF-документа
    pdf.set_meta_info("Author", "Aspose")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```