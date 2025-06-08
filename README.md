# Modelos de Machine Learning - Previsão de Churn

## Objetivo:
Imagine que você seja um Cientista de Dados recém contratado da Telco 
Telecom. Sua primeira tarefa é auxiliar na predição de churn de clientes 
desta empresa de telecomunicações.

O termo "churn" se refere a quando um cliente decide cancelar ou parar de 
usar um serviço.

Você deverá treinar os modelos de classificação que aprendemos durante o 
curso, avaliar e comparar as suas performances. Para isso, você vai utilizar 
também todas as métricas que  foram aprendidas durante o curso. 

## Modelos de classificação utilizados:
- Naive Bayes Multinomial;
- Decision Tree;
- Random Forest;
- XGBoost Classifier;
- Perceptron;
- SVM.

## Performance:

![image](https://github.com/user-attachments/assets/e864749a-56da-4cc6-a626-1df66197256f)

![image](https://github.com/user-attachments/assets/caa6008c-9976-4e50-970a-50966a277b8c)

![image](https://github.com/user-attachments/assets/d64e4121-6d4f-44e4-8c17-e099b4ac509d)

## Conclusão:
- Os três melhores modelos são XGBoost, Random Forest e SVM, todos com concordância moderada de acordo com o Kappa Score;
- Os piores modelos foram o Perceptron e Naive Bayes;
- Dentre os melhores modelos, escolho o XGBoost para colocar em produção, porque é o que possui maior f1-score, demonstrando melhor equilíbrio entre precisão e recall. Além de possuir um parâmetro para classes desbalanceadas (scale_pos_weight.)


