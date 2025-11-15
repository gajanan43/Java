# Set(HashSet,TreeSet,LinkedHashSet):

```
public static void hashset(){
        HashSet<String> set=new HashSet<String>();
        //1-----> Adding elements to the HashSet
        set.add("Red");
        set.add("Green");
        set.add("Blue");
        set.add("Yellow");

        //2-----> Displaying the HashSet
        System.out.println("HashSet: " + set);

        //3-----> Checking if the HashSet contains a specific element
        System.out.println("HashSet contains 'Green': " + set.contains("Green"));

        //4-----> Removing an element from the HashSet
        set.remove("Blue");
        System.out.println("After removing 'Blue': " + set);

        //5-----> Iterating through the HashSet
        System.out.println("Iterating through the HashSet:");
        for(String color:set){
            System.out.println(color);
        }

        //6-----> Size of the HashSet
        System.out.println("Size of the HashSet: " + set.size());

        //7-----> Clearing the HashSet
        set.clear();
    }

    public static void treeset(){
        TreeSet<Double> set=new TreeSet<Double>();
        //1-----> Adding elements to the TreeSet
        set.add(5.5);
        set.add(2.2);
        set.add(8.8);
        set.add(1.1);

        //2-----> Displaying the TreeSet
        System.out.println("TreeSet: " + set);

        //3-----> Checking if the TreeSet contains a specific element
        System.out.println("TreeSet contains 2.2: " + set.contains(2.2));

        //4-----> Removing an element from the TreeSet
        set.remove(5.5);
        System.out.println("After removing 5.5: " + set);

        //5-----> Iterating through the TreeSet
        System.out.println("Iterating through the TreeSet:");
        for(Double num:set){
            System.out.println(num);
        }

        //6-----> Size of the TreeSet
        System.out.println("Size of the TreeSet: " + set.size());

        //7-----> Clearing the TreeSet
        set.clear();
    }   

    public static void linkedhashset(){
        LinkedHashSet<Character> set=new LinkedHashSet<Character>();
        //1-----> Adding elements to the LinkedHashSet
        set.add('A');
        set.add('B');
        set.add('C');
        set.add('D');

        //2-----> Displaying the LinkedHashSet
        System.out.println("LinkedHashSet: " + set);

        //3-----> Checking if the LinkedHashSet contains a specific element
        System.out.println("LinkedHashSet contains 'C': " + set.contains('C'));

        //4-----> Removing an element from the LinkedHashSet
        set.remove('B');
        System.out.println("After removing 'B': " + set);

        //5-----> Iterating through the LinkedHashSet
        System.out.println("Iterating through the LinkedHashSet:");
        for(Character ch:set){
            System.out.println(ch);
        }

        //6-----> Size of the LinkedHashSet
        System.out.println("Size of the LinkedHashSet: " + set.size());

        //7-----> Clearing the LinkedHashSet
        set.clear();
    }   

```
