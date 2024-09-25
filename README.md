# Material React Table
Форк material-react-table (v2.12.1) [github](https://github.com/KevinVandy/material-react-table)

[Документация](https://www.material-react-table.com/)

## Список изменений
1. Отключена задержка обновления состояния фильтров матрицы
2. Фикс бага при очистке input (с типом number), добавлена проверка на пустое поле, чтобы предотвратить ошибку `Value "NaN" cannot be parsed...`

## Установка

[Полная инструкция по установке](https://www.material-react-table.com/docs/getting-started/install)

1. Должен быть установлен React 18 версии и выше

2. Установка зависимостей (Material UI V5)

```bash
npm install @mui/material @mui/x-date-pickers @mui/icons-material @emotion/react @emotion/styled
```

3. Установка inm-mrt

```bash
npm install inm-mrt
```

> _`@tanstack/react-table`, `@tanstack/react-virtual`, and `@tanstack/match-sorter-utils`_ являются внутренними зависимостями, поэтому не нужно устанавливать их самостоятельно.