# Резюме 
*********
### Имя: Ксения Рябова 
### Контакты для связи: 
Телефон: +7-987-432-36-57


Email: crasnowa.kseniya@gmail.com

*********
## Обо мне: 
Люблю и умею быстро учиться чему-то новому. Инициативная - с удовольствием предлагаю и воплощаю что-то новое. Имею большой опыт работы на удаленке, поэтому в совершенстве освоила скилл правильного распределения времени при работе из дома. 
Неконфликтная, спокойная, наслаждаюсь работой в команде.

*********
## Навыки: 
* HTML
* CSS/SASS
* JavaScript (Basic)
* Git
* Java (Basic)
* Figma
* Photoshop

*********
## Пример кода:
```java
import java.util.*;
public class Trip {
    public static void main(String[] args) {
        introduction();
        timeAndBudget();
        timeDifference();
        area();

    }
    public static void introduction() {
        Scanner soon = new Scanner(System.in);
        System.out.println("Welcome to Vacation Planer!");
        System.out.print("What is your name? ");
        String name = soon.nextLine();
        System.out.print("Nice to meet you, " + name + ", " + "where are you travelling to? ");
        String city = soon.nextLine();
        System.out.println("Great! " + city + " " + "sounds like a great trip");
    }
    public static void timeAndBudget() {
        Scanner time = new Scanner(System.in);
        System.out.print("How many days are you going to spend travelling? ");
        int days = time.nextInt();
        System.out.print("How much money, in USD, are you planning to spend on your trip? ");
        int money = time.nextInt();
        System.out.print("What is the three letter currency symbol for your travel destination? ");
        String letter = time.next();
        System.out.print("How many " + letter + " " + "are there in 1 USD? ");
        double currency = time.nextDouble();
        System.out.println("If you are travelling for " + days + " " + "days that is the same as " + days* 24 + " " + "hours or " + days* 1440 + " " + "minutes");
        System.out.println("If you are going to spend " + money + " " + "USD that means that per day you can spend up to" + " " + money/days + " " + "USD");
        System.out.println("Your total budget in " + letter + " " + "is" + " " + money*currency + " " + letter + ", " + "which per day is" + " " + money*currency/days + " " + letter);

    }
    public static void timeDifference() {
        Scanner diff = new Scanner(System.in);
        System.out.print("What is the time difference, in hours, between your home and your destination? ");
        int hours = diff.nextInt();
        System.out.println("That means that when it is midnight at home it will be " + (24 + hours) % 24 + ":00 in your travel destination");
        System.out.println("and when it is noon at home it will be " + (36 + hours) % 24 + ":00");
    }
    public static void area() {
        Scanner area = new Scanner(System.in);
        System.out.print("What is the square area in your destination country in km2? ");
        int square = area.nextInt();
        System.out.println("In miles2 that is " + square*0.621371);
    }
}


*********
## Образование:

		
*********