---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF для Rust через C++"
description: "Получает, является ли PDF-document PDF/A совместимым."
type: docs
url: /ru/rust-cpp/organize/is_pdfa_compliant/
---

_Получает, является ли PDF-document PDF/A совместимым._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Получить статус совместимости PDF/A PDF-document
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```