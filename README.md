# ideas-transpilators-from-to-some-language 
The idea is to write a compiler from some language to a program in the some language or vice versa

# COBOL

transpiler from COBOL to X or from X to COBOL (where X = modern programming language).

--

# in russian:

---
## Идеи транскомпиляторов.

### COBOL

В связи с тем, что (как я читал) из-за эпидемии (пандемии) коронавируса, появился спрос на кобол разработчиков (в связи с чем IBM готовится провести бесплатные курсы по коболу) https://www.cnews.ru/news/top/2020-04-13_ibm_hochet_vozrodit_mertvyj , появилась идея написания транскомпилятора из изходников какого-либо современного языка программирования в код на языке кобол либо наоборот.

Основной профит от этого: привлечение программистов на других языках в поддержку/разработку программ на коболе посредством транскомпиляции программ, написанных на более современном языке в программу на коболе. Либо более простой перенос программ, написанных на коболе, на проограммы на более современном языке программирования.

Возможные варианты языков которые можно использовать в качестве транспилируемого языка: Common Lisp или Scheme, FreeBasic (современный диалект бейсика) или FreePascal, Python, Clojure.
Почему предлагаю на таких языках?
- современные диалекты лиспа (CL, Scheme, Clojure). Лисп - один из старейших языков программирования, программисты на котором вполне моргут быть знакомы с коболом. Также лисп - программируемый язык программирования, поэтому возможно транспилятор с кобола на лисп и с лиспа на кобол будет написать проще, чем на других языках.
- FreeBasic. Бейсик - также достаточно старый язык. Синтаксически более близок к коболу. чем языки с си-подобным синтаксисом.
- FreePascal (или Delphi) - аналогично бейсику имеет синтаксис более близкий к коболу, чем си-подобные языки.
- Python - самый популярный на данный момент язык программирования (наравне с джаваскриптом), на котором уже написан парсер, связанный с кобол ( https://github.com/royopa/python-cobol ).
Но, в принципе, можно написать транспилятор из(в) любого другого современного языка программирования (например из(в) C#, C++ или Java).
