# objectionable-content

Для запуска кода нужно скачать репозиторий и установить все необходимые зависимости. Зависимости прописаны в файле requirements.txt.
Чтобы их установить, нужно ввести в терминале команду `pip install -r requirements.txt`

Чтобы не обучать заново модель, а лишь проверить текст на недопустимость, нужно запустить файл `prediction.ipynb` и в 9 строчке задать переменной `text` свое значение. При этом можно закомментировать строчки 4 - 8, в которых проверяется текст из `data/test.csv`.

![image](https://user-images.githubusercontent.com/49672421/160293199-177057be-cb66-45db-9447-ee54c152dbae.png)
