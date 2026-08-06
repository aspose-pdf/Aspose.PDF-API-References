---
title: "remove_text_footers"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет текстовые колонтитулы из PDF-document."
type: docs
url: /ru/rust-cpp/organize/remove_text_footers/
---

_Удаляет текстовые колонтитулы из PDF-document._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Удалить текстовые колонтитулы из PDF-document
    pdf.remove_text_footers()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```