# validateXML
Скрипт для проверки xml файлов xsd схеме

## Инструкция
Для работы скрипта необходимо указать путь к xsd схеме и путь к папке с xml файлами. Даже если требуется проверить только один файл его необходимо поместить в указанную папку.

**PATH_TO_XSD_SCHEME** - путь к xsd схеме

**PATH_TO_FOLDER_WITH_XML** - путь к папке с файлами xml

В случае если xml файл не соответствует схеме ошибки сохраняются в файле errors.log. По умолчанию этот файл расположен в той же директории откуда запускается скрипт.

## Зависимости
Используется пакет lxml версии 4.5.0