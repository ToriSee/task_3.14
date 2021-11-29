##git commit

**git commit** - совершение коммита.

Чтобы совершить коммит, автоматически индексируя изменения в файлах проекта (новые файлы при этом индексироваться не будут) используйте команду с ключом:

```bash=
git commit -a
```
Чтобы комментировать коммит прямо из командной строки вместо текстового редактора, используйте команду с ключом:

```bash=
git commit -m "commit comment"
```
Чтобы внести в индекс и создать коммит на основе изменений единственного файла, используйте команду:

```bash=
git commit FILENAME
```