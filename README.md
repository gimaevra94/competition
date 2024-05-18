[Соревнование](https://www.kaggle.com/competitions/generated-or-not) представляло из себя попытку определить было ли изображение сгенерированно или нет. Соревнование проводил [Контур](https://kontur.ru/) в качестве отбора лучшиих кандидатов на стажировку в Екатеринбург и Иннополис. Я решил поучавствовать ради личного интереса так как никогда не учавствовал

Изначальные данные были представлены в виде общей папки содержащей как train так и test изображения. В ходе написания кода я отсортировал общую папку images разделив данные на папки train и test.
Помимо images изначальные данные содержали train.csv и test.csv с помощью которых и производилось разделение папки images

Сейчас [данные](https://drive.google.com/file/d/14DOaDLd0g8ft0pBWGKXfhNU4lRzB-Urs/view?usp=drive_link) представлены в виде архива содержащего исходную папку images и папки train и test содержащие разделенные изображения

"competition.ipynb" содержит код соревнования

"correct_names.txt" содержит пути к изображениям и нужен для последущего исправления строк с отсутствующими типами данных в train и test

"sample_submission.csv" содержит пример результирующего файла

"train.csv" имена учебных изображений

"test.csv" имена тестовых изображений
