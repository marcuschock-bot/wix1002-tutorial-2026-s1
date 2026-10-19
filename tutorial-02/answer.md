# Tutorial 02 — Answers

### Question 1a
```java
System.out.print("Faculty of Computer Science ");
System.out.println("and Information Technology.");
```

### Question 1b
```java
System.out.println("Faculty of Computer Science\nand Information Technology.");
```

### Question 2
```java
System.out.println("\"SDN\" - Software-defined networking");
```

### Question 3a
```java
System.out.println("Java Programming");
```

### Question 3b
```java
System.out.println("Introduction to Java!");
```

### Question 3c
```java
System.out.println("\t is the horizontal tab character");
```

### Question 3d
```java
System.out.println("Java is case sensitive!");
```

### Question 4a
```java
String matricNum;
```

### Question 4b
```java
double pi;
```

### Question 4c
```java
boolean M = false;
```

### Question 4d
```java
long P = 8800000000L;
```

### Question 4e
```java
char letter = 'U';
```

### Question 4f
```java
final String PRO = "Java";
```

### Question 5a
```java
double amount = 32.5;
amount += 10;
System.out.println("The amount is " + amount);
```

### Question 5b
```java
String chapter = "Summary";
System.out.println(chapter);
```

### Question 5c
```java
int num = 0;
num++;
int num1 = num;
```

### Question 5d
```java
double num = 3000;
System.out.printf("%4.2f\n", num);
```

### Question 5e
```java
String contact;
Scanner keyboard = new Scanner(System.in);
contact = keyboard.nextLine();
```

### Question 6
```java
import java.util.Scanner;

public class Question6 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter diameter: ");
        double diameter = scanner.nextDouble();
        
        double circumference = Math.PI * diameter;
        
        System.out.printf("The circumference of the circle is: %.3f\n", circumference);
        
        scanner.close();
    }
}
```

### Question 7
```java
import java.util.Scanner;

public class Question7 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter value in inch: ");
        double inch = scanner.nextDouble();
        
        double meters = inch * 0.0254;
        
        System.out.printf("%.2f inches = %.2f meters\n", inch, meters);
        
        scanner.close();
    }
}
```