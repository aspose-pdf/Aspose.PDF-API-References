---
title: "remove_javascripts"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет java scripts из PDF-document."
type: docs
url: /ru/rust-cpp/organize/remove_javascripts/
---

_Удаляет java scripts из PDF-document._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // Удалить JavaScript из PDF-документа
    pdf.remove_javascripts()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```