# List(ArrayList,LinkedList):-

```
public static void arraylist(){
        ArrayList<Integer> list=new ArrayList<Integer>();
        //1-----> Adding elements to the ArrayList
        list.add(35);
        list.add(22);
        list.add(64);
        list.add(50);

        //2-----> Displaying the ArrayList
        System.out.println("ArrayList: " + list);

        //3-----> Accessing elements from the ArrayList
        System.out.println("Element at index 1: " + list.get(1));

        //4-----> Updating an element in the ArrayList
        list.set(1, 20);
        System.out.println("After updating index 1: " + list);

        //5-----> Removing an element from the ArrayList
        list.remove(2);
        System.out.println("After removing element at index 2: " + list);

        //6-----> Iterating through the ArrayList
        System.out.println("Iterating through the ArrayList:");
        for(int num:list){
            System.out.println(num);
        }

        //7-----> Size of the ArrayList
        System.out.println("Size of the ArrayList: " + list.size());

        //8-----> Checking if the ArrayList contains a specific element
        System.out.println("ArrayList contains 20: " + list.contains(20));

        //9-----> sorting the ArrayList
         System.out.println("Sorted ArrayList: ");
         Collections.sort(list);
         System.out.println(list);

       //10-----> reversing the ArrayList
        System.out.println("Reversed ArrayList: ");
        Collections.reverse(list);
        System.out.println(list);

        //11-----> reversing the ArrayList again to get sorted order
        System.out.println("Reversed ArrayList: ");
        Collections.sort(list, Collections.reverseOrder());
        System.out.println(list);

        //12-----> Clearing the ArrayList
        list.clear();
    }

    public static void linkedlist(){
        LinkedList<String> list=new LinkedList<String>();
        //1 Adding elements to the LinkedList
        list.add("Apple");
        list.add("Banana");
        list.add("Cherry");
        list.add("Date");

        //2-----> Displaying the LinkedList
        System.out.println("LinkedList: " + list);

        //3-----> Accessing elements from the LinkedList
        System.out.println("Element at index 2: " + list.get(2));

        //4-----> Updating an element in the LinkedList
        list.set(2, "Citrus");
        System.out.println("After updating index 2: " + list);

        //5-----> Removing an element from the LinkedList
        list.remove(1);
        System.out.println("After removing element at index 1: " + list);

        //6-----> Iterating through the LinkedList
        System.out.println("Iterating through the LinkedList:");
        for(String fruit:list){
            System.out.println(fruit);
        }

        //7-----> Size of the LinkedList
        System.out.println("Size of the LinkedList: " + list.size());

        //8-----> Checking if the LinkedList contains a specific element
        System.out.println("LinkedList contains 'Date': " + list.contains("Date"));

        //9-----> sorting the LinkedList
         System.out.println("Sorted LinkedList: ");
         Collections.sort(list);
         System.out.println(list);

         //10-----> reversing the LinkedList
        System.out.println("Reversed LinkedList: ");
        Collections.reverse(list);
        System.out.println(list);

        //11-----> reversing the LinkedList again to get sorted order
        System.out.println("Reversed LinkedList: ");
        Collections.sort(list, Collections.reverseOrder());
        System.out.println(list);

        //12-----> Clearing the LinkedList
        // list.clear();

        //13 -----> Add element at first position
        list.addFirst("Mango");
        System.out.println("After addFirst: " + list);

        //14 -----> Add element at last position
        list.addLast("Orange");
        System.out.println("After addLast: " + list);

        //15 -----> Get first and last element
        System.out.println("First element: " + list.getFirst());
        System.out.println("Last element: " + list.getLast());

        //16 -----> Remove first and last element
        list.removeFirst();
        list.removeLast();
        System.out.println("After removing first and last: " + list);
    }

```
