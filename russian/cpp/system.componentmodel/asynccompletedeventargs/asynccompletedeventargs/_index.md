---
title: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs конструктор"
linktitle: "AsyncCompletedEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs конструктор. Конструктор в C++."
type: docs
weight: 100
url: /ru/cpp/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Конструктор.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## См. также

* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Инициализирует новый экземпляр класса [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ошибка | const System::Exception\& | Любая ошибка, произошедшая во время асинхронной операции. |
| отменено | bool | Значение, указывающее, была ли асинхронная операция отменена. |
| userState | const System::SharedPtr\<System::Object\>\& | Необязательный пользовательский объект состояния, передаваемый методу [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## См. также

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
