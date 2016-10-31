# LaTeX шаблон для журнала INJOIT
Данный репозиторий содержит LaTeX шаблон статьи для журнала International Journal of Open Information Technologies ([INJOIT](http://injoit.ru/)).
Шаблон основан на шаблоне [IEEEtran LaTeX](http://www.michaelshell.org/tex/ieeetran/).

## Компиляция
**Внимание!** Шаблон не поддерживает компиляцию с помощью `pdflatex`! Используйте `xelatex` (он входит в состав большинства LaTeX дистрибутивов и, скорее всего, уже установлен у вас, если вы используете LaTeX).

Пример компиляции:
```bash
bibtex injoit-rus
xelatex injoit-rus
bibtex injoit-rus
xelatex injoit-rus
``` 

Если вы используете TeXstudio в качестве IDE, вы можете выбрать `xelatex` в качестве компилятора по умолчанию. 
Для этого откройте диалог Options -> Configure TeXstudio -> Build и измените параметр Defualt Compiler.


## Использование шаблона
Внимательно прочтите комментарии в файле `injoit-rus.tex`. Шаблон позволяет:
 * Добавить английское название и аннотацию в конец статьи
 * Добавить колонтитул с выходными данными журнала
 * Изменить номер первой страницы
