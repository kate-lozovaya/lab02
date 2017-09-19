## Laboratory work II

Данная лабораторная работа посвещена изучению утилит для разработки проектов

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Выполнить инструкцию учебного материала
- [x] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**
 
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

- [ar](https://en.wikipedia.org/wiki/Ar_(Unix)) - стандартная утилита Unix, архиватор, не использующий сжатия данных. В настоящее время используется главным образом для создания и обновления статических библиотек.
- [cat](https://en.wikipedia.org/wiki/Cat_(Unix)) - стандартная утилита Unix, которая последовательно считывает и выводит файлы, объединяя их в единый поток.
- [cd](https://en.wikipedia.org/wiki/Cd_(command)) - команда командной строки для изменения текущего рабочего каталога в Unix, DOS, OS/2, AmigaOS, Windows и Linux.
- [cp](https://en.wikipedia.org/wiki/Cp_(Unix)) - команда UNIX для копирования файлов и каталогов.
- [cut](https://en.wikipedia.org/wiki/Cut_(Unix)) - утилита командной строки Unix для выборки отдельных полей из строк файла.
- [echo](https://en.wikipedia.org/wiki/Echo_(command)) - команда в DOS, OS/2, Microsoft Windows, Unix и Unix-подобных операционных системах, которая выводит строки, которые передаются в качестве аргументов.
- [env](https://en.wikipedia.org/wiki/Env_(shell)) - команда для Unix и Unix-подобных операционных систем, исполняющая команду с изменением окружения.
- [ex](https://en.wikipedia.org/wiki/Ex_(editor)) - расширение редактора ed, наиболее значительным добавлением к которому является возможность экранного редактирования, имеет ряд возможностей для одновременной работы с несколькими файлами. 
- [file](https://en.wikipedia.org/wiki/File_(command)) - стандартная программа Unix для распознавания типа данных.
- [find](https://en.wikipedia.org/wiki/Find) - утилита поиска файлов в одном или нескольких каталогах с использованием критериев, заданных пользователем, используемая в UNIX‐подобных операционных системах.
- [ls](https://en.wikipedia.org/wiki/Ls) - команда для вывода списка файлов в Unix и Unix-подобных операционных системах. При вызове без аргументов, команда выдает список файлов в текущей рабочей директории.
- [man](https://en.wikipedia.org/wiki/Man_page) - команда Unix, предназначенная для форматирования и вывода справочных страниц. 
- [mkdir](https://en.wikipedia.org/wiki/Mkdir) - команда для создания новых каталогов в операционных системах Unix, DOS, OS/2 и Microsoft Windows.
- [mv](https://en.wikipedia.org/wiki/Mv) - команда Unix, которая перемещает один или несколько файлов или каталогов из одного места в другое. Если оба имени файлов находятся в одной файловой системе, то это приведет к простому переименованию файла, в противном случае содержимое файла скопируется в новое место, а старый файл удалится.
- [nm](https://en.wikipedia.org/wiki/Nm_(Unix)) - команда в операционной системе UNIX, печатающая информацию о бинарных файлах (объектных файлах, библиотеках, исполняемых файлах и др.), прежде всего таблицу имён.
- [ps](https://en.wikipedia.org/wiki/Ps_(Unix)) - программа в UNIX и Unix-подобных операционных системах, выводящая отчёт о работающих процессах.
- [pwd](https://en.wikipedia.org/wiki/Pwd) - консольная утилита в UNIX-подобных системах, которая выводит полный путь от корневого каталога к текущему рабочему каталогу: в контексте которого (по умолчанию) будут исполняться вводимые команды.
- [rm](https://en.wikipedia.org/wiki/Rm_(Unix)) - утилита в UNIX и UNIX-подобных системах, используемая для удаления файлов из файловой системы.
- [sed](https://en.wikipedia.org/wiki/Sed) - утилита Unix, которая анализирует и преобразует текст, используя простой, компактный язык программирования.
- [touch](https://en.wikipedia.org/wiki/Touch_(Unix)) - стандартная программа интерфейса командной строки Unix, предназначенная для установки времени последнего изменения файла или доступа в текущее время. Также используется для создания пустых файлов.

### Package Managers

- [apt](http://help.ubuntu.ru/wiki/apt) | [dnf](https://en.wikipedia.org/wiki/DNF_(software)) | [yum](https://fedoraproject.org/wiki/Yum/ru) - набор утилит для управления программными пакетами в операционных системах
- [brew](https://brew.sh) | [linuxbrew](http://linuxbrew.sh) - программное обеспечение для управления пакетами
- [npm](https://docs.npmjs.com) - менеджер пакетов, входящий в состав Node.js

### Software

- [curl](https://www.gitbook.com/book/bagder/everything-curl/details) - свободная кроссплатформенная служебная программа командной строки, позволяющая взаимодействовать с множеством различных серверов по множеству различных протоколов с синтаксисом URL.
- [wget](https://www.gnu.org/software/wget/manual/wget.pdf) - свободная неинтерактивная консольная программа для загрузки файлов по сети.
- [clang](https://clang.llvm.org) - является фронтендом для языков программирования C, C++, Objective-C, Objective-C++ и OpenCL C
- [g++](https://gcc.gnu.org/onlinedocs/gcc-4.0.2/gcc/G_002b_002b-and-GCC.html)
- [make](https://en.wikipedia.org/wiki/Make_(software)) - утилита, автоматизирующая процесс преобразования файлов из одной формы в другую.
- [open](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/open.1.html) - команда, которая открывает файл (каталог или URL) так же, как двойной щелчек мыши по иконке.
- [openssl](https://www.openssl.org) -  криптографический пакет с открытым исходным кодом для работы с SSL/TLS. Позволяет создавать ключи RSA, DH, DSA и сертификаты X.509, подписывать их, формировать CSR и CRT. Также имеется возможность шифрования данных и тестирования SSL/TLS соединений.
- [nano](https://www.nano-editor.org) - консольный текстовый редактор для UNIX и Unix-подобных операционных систем, основанный на библиотеке curses и распространяемый под лицензией GNU GPL.
- [tree](https://linux.die.net/man/1/tree) - список содержимого каталогов в древовидном виде.
- [vim](http://www.vim.org) - настраиваемый текстовый редактор, созданный на основе более старого vi, чтобы сделать создание и изменение любого текста эффективным.

```
Copyright (c) 2017 Братья Вершинины
```
