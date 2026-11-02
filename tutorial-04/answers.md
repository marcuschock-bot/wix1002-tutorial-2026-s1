# Tutorial 04 — Answers

### Question 1a
```java
int n = 1;
while ((n + 1) * (n + 1) * (n + 1) < 2000) {
    n++;
}

```

### Question 1b
```java
int i =1;
while (int i <=12){
    System.out.println(i* i);
    i++

}
```

### Question 1c
```java
java.util.Random rand = new java.util.Random();
for (int row = 0; row < 4; row++) {
    for (int col = 0; col < 5; col++) {
        System.out.print(rand.nextInt(101) + "\t");
    }
    System.out.println();
}
```

### Question 1d
```java
int target = input.nextInt();
int sum = 0;

for( int i = 1; i <= target; i++){
    sum+=i;
}
System.out.println("Sum:" + sum);

```

### Question 1e
```java
double sumSeries = 0;
for (int i =1; i<=25; i++){
    sumSeries += (doubles)i/ 26-i;
}
System.out.printf("Sum of series: %2f%n", sumSeries);
```

### Question 2a
```java
int sum = 0;
for (int x = 10; x > 0; x--) {
    sum += x;
}
```

### Question 2b
```java
int x = 0, y = 0;
do {
    x += 2;
    y += x;
    System.out.println(x + " and " + y);
} while (x < 100);
```

### Question 2c
```java
for (int x = -1, y = 20; x < y; x++, y -= 2) {
    // Loop body
}
```

### Question 2d
```java
int x = 1, y = 2;
System.out.println(x + " " + y);
int i = 1;
while (i < 10) {
    if (i == 10) {
        System.out.println("Program End");
    }
    i++;
}
```

### Question 3
```java
int f1 = 1, f2 = 1;
System.out.print(f1 + " " + f2 + " ");

for (int i = 3; i <= 10; i++) {
    int fn = f1 + f2;
    System.out.print(fn + " ");
    f1 = f2;
    f2 = fn;
}
System.out.println();
```

### Question 4
```java
String input = "Java Programming";
String reversed = "";

for (int i = input.length() - 1; i >= 0; i--) {
    reversed += input.charAt(i);
}

System.out.println("Reversed string: " + reversed);
```

