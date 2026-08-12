---
title: "remove_annotations"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет аннотации из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_annotations/
---

_Удаляет аннотации из PDF-документа._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Удалить аннотации из PDF-документа
    pdf.remove_annotations()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```