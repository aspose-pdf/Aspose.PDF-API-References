---
title: "save_docx_enhanced"
second_title: "Aspose.PDF для Rust через C++"
description: "Преобразует и сохраняет ранее открытый PDF-документ как DOCX-документ с режимом расширенного распознавания (полностью редактируемые таблицы и абзацы)."
type: docs
url: /ru/rust-cpp/convert/save_docx_enhanced/
---

_Преобразует и сохраняет ранее открытый PDF-документ как DOCX-документ с режимом расширенного распознавания (полностью редактируемые таблицы и абзацы)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Преобразовать и сохранить ранее открытый PDF-документ как DocX-документ с режимом расширенного распознавания (полностью редактируемые таблицы и абзацы)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```