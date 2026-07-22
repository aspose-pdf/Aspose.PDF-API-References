---
title: "Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages metod"
linktitle: "get_SplitCssIntoPages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages metod. När flersidigt läge är valt (dvs. ''SplitIntoPages'' är ''true'') definierar detta attribut huruvida en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är attributet false, så en stor gemensam CSS‑fil skapas för alla sidor. Den totala storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS‑fil, eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida separat, och då är storleken på varje enskild CSS‑fil det mest kritiska problemet i C++."
type: docs
weight: 2000
url: /sv/cpp/aspose.pdf/htmlsaveoptions/get_splitcssintopages/
---
## HtmlSaveOptions::get_SplitCssIntoPages method


När flersidigt läge är valt (dvs. 'SplitIntoPages' är true) definierar detta attribut om en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är detta attribut false, så en stor gemensam CSS‑fil skapas för alla sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS‑fil, eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida separat, och därmed är storleken på CSS för varje enskild sida det mest kritiska.

```cpp
bool Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages() const
```

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
