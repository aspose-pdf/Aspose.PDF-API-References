---
title: "page_merge_layers"
second_title: "Aspose.PDF för Rust via C++"
description: "Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet."
type: docs
url: /sv/rust-cpp/organize/page_merge_layers/
---

_Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Slå samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```