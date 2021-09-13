# Курс "Практикум на ЭВМ 2021/2022" для бакалавров 3 курса кафедры ММП ВМК МГУ, осенний семестр

Этот репозиторий содержит материалы к курсу "Практикум на ЭВМ", читаемому бакалаврам 3 курса кафедры ММП факультета ВМК МГУ в осеннем семестре 2021 года.



## О курсе

* Обязательный курс для студентов кафедры ММП 3 курса, 5 семестр
* Отчётность: зачёт с оценкой
* В ходе курса студенты выполняют различные практические задания

* Курс читается в поддержку курса "Математические методы распознавания образов" (машинное обучение, часть 1), читаемого на кафедре ММП
  * [Курс лекций по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Курс семинаров по машинному обучению](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)



## Материалы

* Видеозаписи практикумов 2020/2021 года можно посмотреть [в этом плейлисте](https://www.youtube.com/playlist?list=PLVF5PzSHILHRAmJXJvv6_PFzfHf-Zc09Z)

* Материалы прошлого года можно посмотреть [в этом репозитории](https://github.com/mmp-practicum-team/mmp_practicum_fall_2020)

* Большие практические задания [выкладываются здесь](https://github.com/mmp-practicum-team/mmp_practicum_fall_2021/tree/main/Tasks)

* Все задания сдаются в системе [anytask](https://anytask.org/course/830)



## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 02 сентября | 1  | <ul><li>Введение в Python</li></ul> | [Введение в Python](Seminars/Seminar%2001.%20Intro%20to%20Python) | Контест 1: Python |
| 09 сентября | 2  | <ul><li>Векторизация и библиотека Numpy </li></ul> | [Векторизация с помощью Numpy](Seminars/Seminar%2002.%20Vectorization%20with%20Numpy) | Контест 2: Numpy |
| 13 сентября | 3  | <ul><li>Функции, модули, классы</ul></li>| [Функции, модули, классы](Seminars/Seminar%2003.%20Code%20Structure/Code%20structure.pdf) | Контест 3: -  |




## Формат сдачи курса

1. В рамках семестра предполагается три больших практических задания и пять контестов. Все задания сдаются в систему anytask, инвайт к курсу можно получить у преподавателя
2. Каждое большое практическое задание оценивается из **50 баллов**. В больших заданиях предусмотрены различные бонусные активности: бонусные задачи и эксперименты за которые можно получить дополнительные баллы. Задание включает в себя написание программного кода, выполнение экспериментов и написание отчёта о проделанной работе. Последнее практическое задание так же будет включать в себя реализацию работающей ML-системы. По каждому большому заданию предусмотрен **мягкий дедлайн** спустя *две недели* после выдачи задания. После мягкого дедлайна за каждый день просрочки начисляется **штраф 3 балла**. Через *три недели* после выдачи задания наступает **жёсткий дедлайн** и решения сданные позднее на проверку не принимаются. Практическое задание считается зачтённым, если по нему выполнены и засчитаны все три этапа работы
3. За каждый контест можно получить от 8 до 26 баллов (в зависимости от числа заданий в контесте). Задание включает в себя написание программного кода. Срок выполнения каждого контеста — **1 неделя**. Решения, сданные после этого срока, не принимаются на проверку
4. Предварительные критерии итоговой оценки:
   * **отлично ≥ 185 баллов**, 3 практических задания зачтены
   * **хорошо ≥ 139 баллов**, 2 практических задания зачтены
   * **удовлетворительно ≥ 93 баллов**, 1 практическое задание зачтено



# Требования к формату сдачи заданий

## Требования к программному коду

- Код должен в целом соответствовать PEP8 ([eng](https://www.python.org/dev/peps/pep-0008/) или [rus](http://pep8.ru/doc/pep8/) )
- В частности, код должен проходить автоматическую проверку стиля [ссылка](https://github.com/arti32lehtonen/mmp_prac_2017/blob/master/mmp_pep8.py). Скрипт запускается из командной строки так: python3 mmp_pep8.py <ваш скрипт>. Код, вызывающий предупреждения, может дополнительно штрафоваться.
- Код должен быть понятным и единообразным. Переменные, функции и другие элементы кода должны иметь осмысленные, значимые имена, отвечающие их назначению.
- Код, который не соответствует прототипам, выданным в задании, автоматически оценивается в 0 баллов
- Код, который не удовлетворяет требованиям задания (например, запрету на использование конкретных библиотек), автоматически оценивается в 0 баллов
- **Код, содержащий плагиат, автоматически оценивается в 0 баллов**

## Требования к отчёту по практическим заданиям

**Невыполнение данных требований к отчёту будет дополнительно штрафоваться.**

Отчёт должен быть самодостаточным документом в формате PDF, подготовленным в системе LATEX.

**Отчёт должен давать проверяющему ответы на следующие вопросы:**

- К какому курсу относится задание?
- Какое задание выполнено?
- Кем выполнено задание?
- В чём заключалось задание?
- Что было сделано? Что не было сделано?
- Даны ли правильные ответы на все теоретические вопросы задания?
- Проведены ли все необходимые эксперименты? Получены ли осмысленные ВЫВОДЫ?
- Выполнена ли творческая часть задания?
- Пользовался ли студент чьей-либо помощью? Если да, то в каком объёме?
- Какой литературой пользовался студент?

**Некоторые элементы хорошего отчёта:**

- Объём отчёта: 5–20 страниц
- Текст отчёта не повторяет полной формулировки задания
- Структура отчёта соответствует пунктам задания
- Используются векторные шрифты
- Графики оформлены надлежащим образом
- Графики реализованы в векторном формате
- Шкала для графиков выбрана правильно
- На разных графиках результаты для одинаковых методов отображаются одним и тем же цветом
- Между расположением графиков и местами их упоминания в тексте относительно небольшое расстояние (на той же или на соседней странице)
- На страницах не должно быть много пустого места
- В большинстве случаев графики/таблицы/псевдокоды алгоритмов не должны занимать большей части одной страницы отчёта
- Все числа в тексте/таблицах указаны с необходимым числом значащих цифр
- Все формулы реализованы в математическом окружении latex.
- В большинстве случае в отчёте не должно быть никакого кода
- Для всех экспериментов описан выбранный дизайн экспериментов, а также сделаны выводы из полученных результатов
