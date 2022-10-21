
[< к содержанию](./readme.md)

<br>

### Исключение временных и вторичных файлов и директорий.

---

<br>

Git будет игнорировать файлы и директории, перечисленные в файле **.gitignore** с помощью **wildcard** синтаксиса.

````
*.log
build/
temp-*
````

<br>

**git ls-files --others --ignored --exclude-standard** - cписок всех игнорируемых файлов в текущем проекте.

`````
git ls-files --others --ignored --exclude-standard
`````
