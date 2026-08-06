---
title: "remove_tables"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет таблицы из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_tables/
---

_Удаляет таблицы из PDF-документа._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // Удалить таблицы из PDF-документа
    pdf.remove_tables()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```