# Формат данных для обучения

## Требования к данным
Файл с обучающими данными должен быть в формате CSV и содержать следующие столбцы:

- `text`: текст запроса или документа.
- `label`: числовая метка, представляющая класс (например, 0 или 1).

### Пример данных:
```csv
text,label
"Пример текста для обучения",1
"Еще один пример текста",0
