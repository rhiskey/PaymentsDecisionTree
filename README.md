# PaymentsDecisionTree
Data Science Hero lesson materials to predict fraud transactions using decision tree classifier

# Dataset
[Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)
Содержит исторические данные о подозрительных транзакциях, которые могут быть использованы для определения мошеннических действий при проведении платежей.

Все столбцы из набора данных
* step: представляет единицу времени, где 1 шаг равен 1 часу
* type: тип онлайн-транзакции
* amount: сумма транзакции
* nameOrig: клиент, начинающий транзакцию
* oldbalanceOrg: баланс до транзакции
* newbalanceOrig: баланс после транзакции
* nameDest: получатель транзакции
* oldbalanceDest: начальный баланс получателя перед транзакцией
* newbalanceDest: новый баланс получателя после транзакции
* isFraud: флаг подозрительной транзакции
