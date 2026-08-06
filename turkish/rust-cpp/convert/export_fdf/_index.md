---
title: "export_fdf"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "AcroForm içeren daha önce açılmış PDF-belgesinden dosya adıyla FDF-belgesine dışa aktarır."
type: docs
url: /tr/rust-cpp/convert/export_fdf/
---

_AcroForm içeren daha önce açılmış PDF-belgesinden dosya adıyla FDF-belgesine dışa aktarır._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // AcroForm içeren daha önce açılmış PDF-belgesinden FDF-belgesine dışa aktar
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```