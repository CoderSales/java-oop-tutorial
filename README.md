# java-oop-tutorial
java-oop-tutorial | preparatory for ArrayList tutorial

## Content

### Input

```bash
$ javac Bicycle.java
```

### Output

```bash
cadence:0 speed:0 gear:1
```

### Code (basically except it's BicycleModified.java not Bicycle.java)

```java
class BicycleModified {int cadence = 0;
                       int speed = 0;
                       int gear = 1;
    void changeCadence(int newValue) {cadence = newValue;}
    void changeGear   (int newValue) {gear = newValue;}
    void speedUp      (int increment){speed += increment;}
    void applyBrakes  (int decrement){speed -= decrement;}
    void printStates  () {System.out.println("cadence:" + cadence 
                                           + " speed:" + speed
                                           + " gear:" + gear);}
    public static void main(String[] args) {
        BicycleModified bicycle1 = new BicycleModified();
        bicycle1.printStates();}}
```

## References

java oop tutorial [Objects, Classes, Interfaces, Packages, and Inheritance](https://dev.java/learn/oop/)
