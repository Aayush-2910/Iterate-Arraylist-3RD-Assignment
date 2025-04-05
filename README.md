# Iterate-Arraylist-3RD-Assignment
# This is my first Repos on topic Iterate Arraylist

import java.util.ArrayList;

public class ArrayListIterationExample {
    public static void main(String[] args) {
        // Create and populate the ArrayList
        ArrayList<String> fruits = new ArrayList<>();
        fruits.add("Apple");
        fruits.add("Banana");
        fruits.add("Cherry");
        fruits.add("Date");
        fruits.add("Elderberry");

        System.out.println("Iterating using traditional for-loop:");
        for (int i = 0; i < fruits.size(); i++) {
            System.out.println(fruits.get(i));
        }

        System.out.println("\nIterating using while-loop:");
        int index = 0;
        while (index < fruits.size()) {
            System.out.println(fruits.get(index));
            index++;
        }

        System.out.println("\nIterating using enhanced for-loop:");
        for (String fruit : fruits) {
            System.out.println(fruit);
        }
    }
}
