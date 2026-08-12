---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF для Rust через C++"
description: "Удалить соответствие PDF/A из PDF-документа."
type: docs
url: /ru/rust-cpp/organize/remove_pdfa_compliance/
---

_Удалить соответствие PDF/A из PDF-document._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Удалить соответствие PDF/A из PDF-документа
    pdf.remove_pdfa_compliance()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```