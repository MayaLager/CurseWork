# CurseWork
Данный проект направлен на автоматическое определение мотевационных паттернов: стремление и избегание по интервью.

Состоит из:

    1.Интервью_русские --- папка с реальными интервью, на которых происходит тестирование(там 7 файлов, названия имеют вид: Test{i}.docx
    
    2.InterviewRussian.xlsx --- таблица с этими 7 интервью, каждое разбито по диалогам(вопрос + ответ) и поставлен класс(-1, 0, 1, соответственно для избегания, нейтрально, стремления)
    
    3.MotivationPatterns.ipynb --- colab, где происходило обучение модели и ее тестирование
    
    4.TrainDatasetCurs.xlsx --- сама таблица из 10716 записей, на которой потом происходит обучение модели
