package Lesson1;

public class HomeWorkApp {
    public static void main(String[] args) {
        helloUser();
        calculate();
        printColor();
        printThreeWords();
        compareNumbers();
    }

    public static void printThreeWords() {
        System.out.println("Orange");
        System.out.println("Banana");
        System.out.println("Apple");
    }

    public static void helloUser() {
        System.out.println("Hello User");
    }

    public static void calculate() {
        System.out.println(5 + 5);
    }

    public static void printColor() {
        int x = 112;
        if (x > 100) {
            System.out.println("green");
        } else if (x > 0) {
            System.out.println("yellow");
        } else {
            System.out.println("red");
        }
    }

    public static void compareNumbers() {
        int a = 6;
        int b = 5;
        if (a >= b) {
            System.out.println("a>=b");
        }
    }
}
