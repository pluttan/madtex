![Header](header.png)

<div align="center">

# MaDTeX

**Конвертер Markdown в LaTeX со встроенным выполнением Python**

[![License](https://img.shields.io/badge/license-MIT-2C2C2C?style=for-the-badge&labelColor=1E1E1E)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.x-2C2C2C?style=for-the-badge&logo=python&labelColor=1E1E1E)]()
[![Pandoc](https://img.shields.io/badge/pandoc-required-2C2C2C?style=for-the-badge&labelColor=1E1E1E)]()
[![LaTeX](https://img.shields.io/badge/latex-output-2C2C2C?style=for-the-badge&logo=latex&labelColor=1E1E1E)]()

</div>

Конвертирует Markdown в LaTeX: сначала прогоняет файл через Pandoc (`markdown` в HTML), затем транслирует полученные HTML-теги в LaTeX с помощью собственного рекурсивного парсера. Инлайн-формулы `$...$` и блочные `$$...$$` извлекаются до конвертации и восстанавливаются без изменений после. Поддерживается встроенный режим Python — код внутри специальных HTML-комментариев `exec`'ится в процессе конвертации, а его stdout вставляется в LaTeX-документ.

## ■ Возможности

- ❖ **Markdown в LaTeX** — заголовки, списки, таблицы, ссылки, жирный/курсив, зачёркивание, цитаты, списки определений
- ❖ **Сохранение формул** — инлайн `$...$` и блочные `$$...$$` извлекаются до конвертации и восстанавливаются дословно
- ❖ **Блоки кода** — огороженный код преобразуется в `lstlisting`, язык ограждения переносится как `[language = ...]`
- ❖ **Встроенный Python** — теги `<!-- *code -->` запускают `exec()` и вставляют перехваченный stdout (`import`/`sys.` заблокированы)
- ❖ **Сырой LaTeX** — теги `<!-- ?\macro -->` передают сырой LaTeX напрямую в вывод
- ❖ **Пользовательские команды** — `~whodo` (автор), `~note` (сноски), `~reflist`/`~ereflist` (списки ссылок с гиперссылками), записанные как HTML-комментарии
- ❖ **Поддержка изображений** — Markdown-изображения конвертируются в макрос `\image{src}{caption}`
- ❖ **Комментарии LaTeX** — обычные теги `<!-- text -->` становятся `% text`

## ■ Стек

<div align="center">

| Компонент | Технология |
|-----------|------------|
| Конвертер | Python (single script) |
| MD в HTML | Pandoc (external) |
| Парсер | Custom recursive HTML to LaTeX |
| Формулы | LaTeX math mode |
| Вывод | LaTeX (`.tex`) |

</div>

## ■ Запуск

```bash
# Requires `pandoc` on PATH.
# The input file is hard-coded as exam.md at the bottom of the script.
python MaDTeX.py

# Produces:
#   conf/exam.html  — intermediate Pandoc HTML
#   conf/exam.tex   — generated LaTeX source
```

> Примечание: сгенерированный `.tex` содержит жёстко прописанный путь к преамбуле
> (`/Users/pluttan/Documents/forMyDocs/preamb.tex`); компиляцию в PDF выполнять отдельно.

## ■ Скриншоты

<div align="center">

![Screenshot](screenshots/main.png)

*Результат основной конвертации — сгенерированный LaTeX-источник из Markdown-ввода*

</div>

## ■ License

MIT © [pluttan](https://github.com/pluttan)
