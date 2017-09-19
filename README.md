## Laboratory work II

Данная лабораторная работа посвещена изучению утилит для разработки проектов

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [ ] 2. Выполнить инструкцию учебного материала
- [ ] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**
 
## Tutorial

```bash
$ export GITHUB_USERNAME=<имя_пользователя>
$ export GIST_TOKEN=<сохраненный_токен>
$ alias edit=<nano|vi|vim|subl>
```

```bash
$ npm install -g gistup
```

```bash
$ cat > ~/.gistup.json <<EOF
{
  "token": "${GIST_TOKEN}"
}
EOF
```

```bash
$ cd ~
$ mkdir -p workspace/labs/projects/
$ mkdir -p workspace/labs/tasks/
$ mkdir -p workspace/labs/reports/
```

## Report

```bash
$ cd ~/workspace/labs/
$ export LAB_NUMBER=02
$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}
$ mkdir reports/lab${LAB_NUMBER}
$ cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md
$ cd reports/lab${LAB_NUMBER}
$ edit REPORT.md
$ gistup -m "lab${LAB_NUMBER}"
```

## Links

### Unix commands

- [ar](https://en.wikipedia.org/wiki/Ar_(Unix))//Стандартная утилита Unix, архиватор, не использующий сжатия данных. В настоящее время используется главным образом для создания и обновления статических библиотек.
- [cat](https://en.wikipedia.org/wiki/Cat_(Unix))//Cтандартная утилита Unix, которая последовательно считывает и выводит файлы, объединяя их в единый поток.
- [cd](https://en.wikipedia.org/wiki/Cd_(command))//Команда командной строки для изменения текущего рабочего каталога в Unix, DOS, OS/2, AmigaOS, Windows и Linux.
- [cp](https://en.wikipedia.org/wiki/Cp_(Unix))//Команда UNIX для копирования файлов и каталогов.
- [cut](https://en.wikipedia.org/wiki/Cut_(Unix))//Утилита командной строки Unix для выборки отдельных полей из строк файла.
- [echo](https://en.wikipedia.org/wiki/Echo_(command))//Команда в DOS, OS/2, Microsoft Windows, Unix и Unix-подобных операционных системах, которая выводит строки, которые передаются в качестве аргументов.
- [env](https://en.wikipedia.org/wiki/Env_(shell))//Команда для Unix и Unix-подобных операционных систем, исполняющая команду с изменением окружения.
- [ex](https://en.wikipedia.org/wiki/Ex_(editor))//Расширение редактора ed, наиболее значительным добавлением к которому является возможность экранного редактирования, имеет ряд возможностей для одновременной работы с несколькими файлами. 
- [file](https://en.wikipedia.org/wiki/File_(command))//
- [find](https://en.wikipedia.org/wiki/Find)//
- [ls](https://en.wikipedia.org/wiki/Ls)//
- [man](https://en.wikipedia.org/wiki/Man_page)//
- [mkdir](https://en.wikipedia.org/wiki/Mkdir)//
- [mv](https://en.wikipedia.org/wiki/Mv)//
- [nm](https://en.wikipedia.org/wiki/Nm_(Unix))//
- [ps](https://en.wikipedia.org/wiki/Ps_(Unix))//
- [pwd](https://en.wikipedia.org/wiki/Pwd)//
- [rm](https://en.wikipedia.org/wiki/Rm_(Unix))//
- [sed](https://en.wikipedia.org/wiki/Sed)//
- [touch](https://en.wikipedia.org/wiki/Touch_(Unix))//

### Package Managers

- [apt](http://help.ubuntu.ru/wiki/apt) | [dnf](https://en.wikipedia.org/wiki/DNF_(software)) | [yum](https://fedoraproject.org/wiki/Yum/ru)
- [brew](https://brew.sh) | [linuxbrew](http://linuxbrew.sh)
- [npm](https://docs.npmjs.com)

### Software

- [curl](https://www.gitbook.com/book/bagder/everything-curl/details)
- [wget](https://www.gnu.org/software/wget/manual/wget.pdf)
- [clang](https://clang.llvm.org)
- [g++](https://gcc.gnu.org/onlinedocs/gcc-4.0.2/gcc/G_002b_002b-and-GCC.html)
- [make](https://en.wikipedia.org/wiki/Make_(software))
- [open](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/open.1.html)
- [openssl](https://www.openssl.org)
- [nano](https://www.nano-editor.org)
- [tree](https://linux.die.net/man/1/tree)
- [vim](http://www.vim.org)

```
Copyright (c) 2017 Братья Вершинины
```
