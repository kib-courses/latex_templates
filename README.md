# latex_templates
LaTeX шаблоны для спецкурсов, открытых лекций и других мероприятий

## Установка LaTeX и TexStudio

Мне не жалго 4Gb памяти, поэтому я установил всё:

```bash
~$ sudo apt update
~$ sudo apt install texlive-full
```
Установка занимает около 30 минут времени. Поэтому запускаем и идём пить чай. 

Плюсы: всегда всё будет работать. 
Минусы: 4 гигабайта, нужно 30 минут устанавливать.

Если хотите, можете устанавливать пакетами, но будте готовы что что-то будет не работать и нужно будет доустанавливать

После нужно установить [TeXStudio](https://www.texstudio.org):

```bash
~$ sudo apt install texstudio
```

## Работа с шаблоном

В TeXStudio зайдите **Options --> Configure TeXStudio**.
Во вкладке **Build** поменяйте **Default Compiler** на **LuaLaTeX**. 
Остальное оставте без изменения

Перетащите папки **xx_lecture**, **header** **pic** в свой проект.

Перетащите .gitignore

Переименуйте файл **xx_lecture/xx_lecture.tex** в номер лекции вашего спецкурса.
Переименуйте папку **xx_lecture** в номер лекции вашего спецкурса.

С помощью **git add** заносите только **tex** файлы и картинки.

Когда лекция будет готова, можете её тоже сохранить в корне проекта, назвав её так же как и **xx_lecture** папку.

## Вопросы

Пишите Павлу Слипенчуку
