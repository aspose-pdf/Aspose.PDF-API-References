---
title: "export_xml"
second_title: "Aspose.PDF для Rust через C++"
description: "Экспорт из ранее открытого PDF‑документа с AcroForm в XML‑документ с именем файла."
type: docs
url: /ru/rust-cpp/convert/export_xml/
---

_Экспорт из ранее открытого PDF‑документа с AcroForm в XML‑документ с именем файла._

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
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

    // Экспорт из ранее открытого PDF‑документа с AcroForm в XML‑документ
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```