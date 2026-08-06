---
title: "page_merge_layers"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmana birleştirir."
type: docs
url: /tr/rust-cpp/organize/page_merge_layers/
---

_Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmana birleştirir._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmana birleştir
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```