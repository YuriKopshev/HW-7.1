# Информация по счётчикам JaCoCo

## 1. INSTRUCTION(Инструкции)
Самая маленькая единица измерения JaCoCo - это одиночные инструкции кода байта Java. Покрытие инструкции предоставляет информацию о количестве кода, который был выполнен или пропущен. Эта метрика полностью независима от исходного форматирования и всегда доступна даже в отсутствие отладочной информации в файлах классов.

## 2. BRANCH (Ветви)
JaCoCo также вычисляет охват веток для всех операторов if и switch. Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей.

## 3. LINE(Линии)
Для всех файлов классов, которые были скомпилированы с информацией об отладке, можно рассчитать информацию о покрытии для отдельных строк. Исходная строка считается выполненной, когда была выполнена хотя бы одна команда, назначенная этой строке.
