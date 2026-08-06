---
title: "remove_blank_pages"
second_title: "Aspose.PDF для Rust через C++"
description: "Удаляет пустые страницы из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_blank_pages/
---

_Удаляет пустые страницы из PDF-документа._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Удалить пустые страницы из PDF-документа
    pdf.remove_blank_pages()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```