# Tutorial 03 — Answers

### Question 1a
```java
if (3 * 8 == 27) {
    System.out.println("3 * 8 is equal to 27");
} else {
    System.out.println("3 * 8 is not equal to 27");
}
```

### Question 1b
```java
if (num % 2 == 0) {
    System.out.println("Even number");
} else {
    System.out.println("Odd number");
}
```

### Question 1c
```java
if (ch >= 'A' && ch <= 'Z') {
    System.out.println("Capital letter");
}
```

### Question 1d
```java
if (str1.compareToIgnoreCase(str2) <= 0) {
    System.out.println(str1 + "\n" + str2);
} else {
    System.out.println(str2 + "\n" + str1);
}
```

### Question 1e
```java
switch (day) {
    case 0:
        System.out.println("Sunday");
        break;
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    case 3:
        System.out.println("Wednesday");
        break;
    case 4:
        System.out.println("Thursday");
        break;
    case 5:
        System.out.println("Friday");
        break;
    case 6:
        System.out.println("Saturday");
        break;
}
```

### Question 2a
```java
if (num1 == num2)
    System.out.println("Number 1 is equal to number 2.");
```

### Question 2b
```java
if (x > y && y > z)
    System.out.println("x is the largest number");
```

### Question 2c
```java
String s1, s2;
if (s1.equals(s2))
    System.out.println("They are equal strings.");
else
    System.out.println("They are not equal strings.");
```

### Question 2d
```java
if (x > 0 || y > 0)
    System.out.println("Either x or y is positive");
```

### Question 3a
```
#####
$$$$$
```

### Question 3b
```
#####
$$$$$
```

### Question 3c
```
#####
```

### Question 3d
```
(No output)
```

### Question 4
```java
int max = a;
if (b > max) {
    max = b;
}
if (c > max) {
    max = c;
}
System.out.println("The biggest number is: " + max);
```

### Question 5
```java
boolean isLeapYear = (year % 4 == 0 && year % 100 != 0) || (year % 400 == 0);
if (isLeapYear) {
    System.out.println(year + " is a leap year.");
} else {
    System.out.println(year + " is not a leap year.");
}
```