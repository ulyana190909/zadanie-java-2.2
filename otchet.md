# Отчёт о тестировании приложения "Бонусная система"
#### Дата провередения тестирования: 10.07.2020.

#### На тестирование был потрачен 1 час.

### Проведено функциональное тестирование приложения "Бонусная система" . Результат тестирования должен был показать насколько корректно отражается количество бонусов при сложении показателей.
### Результат тестирования показал, что расчет бонусов не точный.
**В процессе тестирования использовался следующий код:**

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

**Результат тестирования кода:**
```
"C:\Program Files\Java\jdk-11.0.7\bin\java.exe" -javaagent:C:\Users\79269\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\201.7846.76\lib\idea_rt.jar=53708:C:\Users\79269\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\201.7846.76\bin -Dfile.encoding=UTF-8 -classpath C:\Users\79269\IdeaProjects\untitled\out\production\untitled Main
0.8999999999999999

Process finished with exit code 0
```

**По результату заведен BAG Report** - https://github.com/ulyana190909/zadanie-java-2.2/issues/1


**Тестирование производилось в следующем окружении:**
* HP Pavilion Gaming, Windows 10
* Java - openjdk version "11.0.7" 2020-04-14
* javac 11.0.7
* IntelliJ IDEA