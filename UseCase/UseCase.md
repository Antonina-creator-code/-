UseCase диаграмма патент
![image](https://github.com/user-attachments/assets/e8302fca-5f54-4b6e-ae0f-cce915605e9f)

# Акторы:
Иностранный гражданин - человек, планирующий работать в России

Сотрудник УМВД России / ФГУП «ПВС» МВД России - человек, принимающий заявки на получение патента

Администратор - человек, который проверяет заявления

### Прецеденты (use case)

#### Use case 1: Войти в систему

* **Акторы**: *сотрудник УМВД / сотрудник ФГУП / администратор / иностранный гражданин*

* **Описание**: Актор вводит свои учетные данные для доступа к системе
#### Use case 2: Заполнить заявление

* **Актор**: *иностранный гражданин*

* **Описание**: Иностранный гражданин заполняет заявление на получение патента, удостоверяясь, что все данные верны

#### Use case 3: Получить уведомление о принятии заявления

* **Актор**: *иностранный гражданин*

* **Описание**: После подачи заявления и документов иностранный гражданин получает уведомление о статусе своего заявления

#### Use case 4: Получить отказ или одобрение патента

* **Актор**: *иностранный гражданин*

* **Описание**: Иностранный гражданин получает решение о выдаче патента после обработки своего заявления

#### Use case 5: Обратиться в УМВД России / ФГУП

* **Актор**: *иностранный гражданин*

* **Описание**: Иностранный гражданин подает заявление и все сопутствующие документы в УМВД или ФГУП «ПВС»

#### Use case 6: Проверить заявления

* **Актор**: *Администратор*

* **Описание**: Администратор проверяет поданные заявления и документы на соответствие требованиям

#### Use case 7: Обработать заявления

* **Актор**: *Сотрудник УМВД России / ФГУП «ПВС» МВД России*

* **Описание**: Сотрудник УМВД рассматривает поданные заявления и фиксирует их статус в системе

#### Use case 8: Выдать патент или отказать

* **Актор**: *Сотрудник УМВД России / ФГУП «ПВС» МВД России*

* **Описание**: Сотрудник УМВД принимает решение об одобрении или отказе на патент исходя из требований
# UseCase иностранного гражданина:
Иностранный гражданин --> входит в систему

Иностранный гражданин --> обращается в УМВД России / ФГУП «ПВС» МВД России

Иностранный гражданин --> заполняет заявление на получение патента

Иностранный гражданин --> получает уведомление о принятии заявления

Иностранный гражданин --> получает одобрение или отказ в патенте

# UseCase сотрудника УМВД России / ФГУП «ПВС» МВД России:
Сотрудник УМВД России / ФГУП «ПВС» МВД России --> входит в систему

Сотрудник УМВД России / ФГУП «ПВС» МВД России --> одобряет или отказывает в получении патента

# UseCase администратора:
Администратор --> входит в систему

Администратор --> проверяет заявления





