---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF для Rust через C++"
description: "Удалить соответствие PDF/UA из PDF-document."
type: docs
url: /ru/rust-cpp/organize/remove_pdfua_compliance/
---

_Удалить соответствие PDF/UA из PDF-document._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
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

    // Удалить соответствие PDF/UA из PDF-документа
    pdf.remove_pdfua_compliance()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```