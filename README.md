# Датасет по банковским вкладам в г. Москва #

## Описание ##
В рамках данного датасета проведена агрегация данных по условиям вкладов разных банков в г. Москва. 
Данная информация может быть использована как потенциальными клиентами для выбора наиболее подходящего вклада в зависимости от их потребностей, так и финансовыми учреждениями для сравнения своих предложений по вкладам относительно предложений своих конкурентов.

С учетом того, что во многих вкладах доходность зависит от размещенной на вкладе суммы, все возможные варианты доходности по одному вкладу перечислены в датасете в виде отдельных строк с указанием ставки и диапазона суммы, в рамках которой применяется ставка.

## Источники ##
1. https://www.banki.ru/products/deposits/

## Структура ##
Типы полей указаны согласно типов в Python
- Банк (тип поля - str)
- Финансовый рейтинг надежности банка	(по общим активам) (тип поля - str)
- Название вклада (тип поля - str)
- Дата начала действия предложения (тип поля - str в формате yy.MM.dddd)	
- Дата окончания действия предложения (тип поля - str в формате yy.MM.dddd)
- Ставка, % годовых (тип поля - float)
- Минимальный срок вклада, дни (тип поля - int)
- Максимальный срок вклада, дни	(тип поля - int)
- Минимальная сумма вклада, руб. (для указанной в строке ставки) (тип поля - int)
- Максимальная сумма вклада, руб.	(для указанной в строке ставки) (тип поля - int)
- Возможность пополнения (да/нет/условия)	(тип поля - str)
- Возможность расторжения	(да/нет/условия) (тип поля - str)
- Частичное снятие (да/нет/условия)	(тип поля - str)
- Капитализация	(способ капитализации) (тип поля - str)
- Дополнительные условия (в виде списка) (тип поля - list)
