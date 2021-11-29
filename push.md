## git push

**git push** - вносит изменения в удаленный репозиторий.

Чтобы отправить свои изменения в удаленную ветку, созданную при клонировании по умолчанию, используют команду:

```bash=
git push 
```

Чтобы отправить изменения из ветки master в ветку experimental удаленного репозитория, используют команду:

```bash=
git push ssh://yourserver.com/~you/proj.git master:experimental
```

Чтобы в удаленном репозитории origin удалить ветку experimental, используют команду:

```bash=
git push origin :experimental
```

Чтобы в удаленную ветку master репозитория origin (синоним репозитория по умолчанию) ветки локальной ветки master, используйте команду:

```bash=
git push origin master:master
```

Чтобы отправить метки в удаленную ветку master репозитория origin, используйте команду:

```bash=
git push origin master --tags
```

Чтобы изменить указатель для удаленной ветки master репозитория origin (master будет такой же как и develop), используйте команду:

```bash=
git push origin origin/develop:master
```
Чтобы добавить ветку test в удаленный репозиторий origin, указывающую на коммит ветки develop, используйте команду:

```bash=
git push origin origin/develop:refs/heads/test
```