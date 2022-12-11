# ИНСТРУКЦИЯ ПО РАБОТЕ С GIT

![Logo GIT](img/Git-Logo-1788C.png)

---

[<<](init-git.md) | [Содержание](../readme.md) -> Запрет на включение в репозиторий файлов и папок | [>>](local-git.md)

---

## Запрет на включение в репозиторий файлов и папок

### Создание файла .gitignore

В рабочей папке содать файл с наименованием .gitignore

Правила синтаксиса:

1. Одна строчка - одно правило.
2. Пустые строки игнорируются.
3. Комментарии доступны через решётку (#) в начале строки.
4. Символ "/" в начале строки указывает, что правило применяется только к файлам и папкам, которые располагаются в той же папке, что и сам файл .gitignore.
5. Доступно использовать спецсимволы: звёздочка (\*) заменяет любое количество символов(ноль или больше), вопрос (?) заменяет от нуля до одного символа.
6. Две звёздочки (\*\*) используются для указания любого количества поддиректорий.
7. Восклицательный знак (!) в начале строки означает инвертирование правила.
8. Символ "\\" используется для экранирования спецсимволов.
9. Для игнорирования всей директории, правило должно оканчиваться на слэш (/).

---

Copyright 2022 Arkhipov Andrey

> Licensed under the Apache License, Version 2.0 (the "License");
> You may not use this file except in compliance with the License.
> You may obtain a copy of the License at
> [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
> Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
> See the License for the specific language governing permissions and limitations under the License.

---

Git Logo by Jason Long - [https://git-scm.com/downloads/logos,](https://git-scm.com/downloads/logos)

> licensed under the [Creative Commons Attribution 3.0 Unported License.](https://creativecommons.org/licenses/by/3.0/)

---
