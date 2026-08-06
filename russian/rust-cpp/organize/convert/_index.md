---
title: "convert"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует PDF-документ в PDF-документ с указанным форматом PDF."
type: docs
url: /ru/rust-cpp/organize/convert/
---

_Преобразует PDF-документ в PDF-документ с указанным форматом PDF._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Конвертировать PDF-документ в PDF-документ с указанным форматом PDF
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Вывести результат конвертации и полный журнал
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```