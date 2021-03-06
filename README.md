# Отчёт о тестировании Main.java на ОС Windows 10

## Краткое описание
Проверка работоспособности кода.

## Описание тестов
Проводилось позитивное функциональное тестирование.

>Шаг 1. Открыла IDEA

>Шаг 2. Создала новый проект и добавила код

```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

>Шаг 3. Создала конфигурацию запуска клавишами Ctrl + Shift + F10

## Результаты
100% успешный тест

Код успешно и корректно отработал. Итоговая сумма бонусов клиентов (totalBonus) - положительное значение, больше заявленнного значения regularBonus. 

![img](https://github.com/voevodina/images/blob/master/Main_3.png?raw=true)

## Общие рекомендации
Необходимо внимательно следить за тем, чтобы итоговое значение (суммарное значение бонусов) не было отрицательным значением и не было меньше заявленых, поскольку изначально все таки речь о дополнительном бонусе. То есть, итоговая цифра должна быть больше изначальной regularBonus. 
