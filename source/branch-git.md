# ИНСТРУКЦИЯ ПО РАБОТЕ С GIT

![Logo GIT](img/Git-Logo-1788C.png)

---

[<<](local-git.md) | [Содержание](../readme.md) -> Работа с ветками в GIT | [>>](merge-git.md)

---

## Работа с ветками в GIT

### Создание новой ветки

```
git branch fix
```

> _Указать наименование создаваемой ветки_

```
git checkout -b fix
```

> _Создание новой ветки с одновременным переходом на нее_

![git branch fix](img/git-branch-fix.png)

### Просмотр существующих ветвей

```
git branch
```

### Переход на соседнюю ветку

```
git checkout fix
```

> _Указать наименование ветки_

### Удаление ветки

```
git branch -d fix
```

![git branch -d](img/git-branch-d.png)

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
