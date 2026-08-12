---
title: "remove_attachments"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет вложения из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_attachments/
---

_Удаляет вложения из PDF-документа._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // Удалить вложения из PDF-документа
    pdf.remove_attachments()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```