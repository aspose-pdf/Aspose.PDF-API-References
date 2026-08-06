---
title: "clear_meta_info"
second_title: "Aspose.PDF для Rust через C++"
description: "Очищает все значения метаданных PDF-документа."
type: docs
url: /ru/rust-cpp/core/clear_meta_info/
---

_Очищает все значения метаданных PDF-документа._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Очистить все значения метаданных PDF-документа
    pdf.clear_meta_info()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```