---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF для Rust через C++"
description: "Получает, является ли PDF-document PDF/UA совместимым."
type: docs
url: /ru/rust-cpp/organize/is_pdfua_compliant/
---

_Получает, является ли PDF-document PDF/UA совместимым._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // Получить статус совместимости PDF/UA PDF-document
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```