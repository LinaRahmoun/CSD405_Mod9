# CSD405_Mod9

#Expression that takes two integers and returns the sum

(int a, int b) -> a + b

#Runnable interface

Runnable runnable = () -> {

#forEach method

List<String> names = Arrays.asList("Ryan", "Eddie", "Anna");
names.forEach(name -> System.out.println(name));

#Sorting bsed on specific criteria

List<Integer> numbers = Arrays.asList(3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5);
numbers.sort((a, b) -> a.compareTo(b));
