# Отчёт о тестировании Precision

## Краткое описание

14.06.2021 было проведено тестирование приложения по внедрению дополнительных бонусов новым клиентам.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [Неверное значение в итоговой переменной при расчете бонуса клиентам](https://github.com/AndrewShch/javaQA.Shchepkin.lesson2.task2/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные из [задачи №2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):

```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тестирование производилось в следующем окружении:
* ОС Windows 10 (64x)
* Java 11