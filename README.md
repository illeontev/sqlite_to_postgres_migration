# Перенос данных из SQLite в PostgreSQL

main.py - главный скрипт, который запускает процесс миграции данных;

sqlite_loader.py - содержит описание класса, который используется для выгрузки данных из SQLite;

postgres_saver.py - содержит описание класса, который используется для загрузки данных в PostgreSQL;

service_db.py - содержит функции для создания запросов;

db_dataclasses.py - содержит описание вспомогательных классов;

tables_settings.py - содержит описание настроек для выгружаемых таблиц;


check_consistency.py - файл с тестами (Pytest);

.env - файл с переменными окружения. В паблике такое лучше не постить, конечно;

db.sqlite - файл с базой данных SQLite.


