---
title: "validate"
second_title: "Aspose.PDF для Rust через C++"
description: "Проверяет PDF-документ на соответствие формату PDF."
type: docs
url: /ru/rust-cpp/organize/validate/
---

_Проверяет PDF-документ на соответствие формату PDF._

```rust
    pub fn validate(
        &self,
        pdf_format: PdfFormat,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the validation log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Проверить PDF-документ на соответствие формату PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Вывести результат проверки и полный журнал
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```