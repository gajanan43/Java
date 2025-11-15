# Map(HashMap,TreeMap,LinkedListMap):

```
public static void hashmap(){
        HashMap<Integer, String> map=new HashMap<Integer, String>();
        //1-----> Adding key-value pairs to the HashMap
        map.put(1, "One");
        map.put(2, "Two");
        map.put(3, "Three");
        map.put(4, "Four");

        //2-----> Displaying the HashMap
        System.out.println("HashMap: " + map);

        //3-----> Accessing a value by key from the HashMap
        System.out.println("Value for key 2: " + map.get(2));

        //4-----> Updating a value in the HashMap
        map.put(2, "Twenty");
        System.out.println("After updating key 2: " + map);

        //5-----> Removing a key-value pair from the HashMap
        map.remove(3);
        System.out.println("After removing key 3: " + map);

        //6-----> Iterating through the HashMap
        System.out.println("Iterating through the HashMap:");
        for(Map.Entry<Integer, String> entry : map.entrySet()){
            System.out.println("Key: " + entry.getKey() + ", Value: " + entry.getValue());
        }

        //7-----> Size of the HashMap
        System.out.println("Size of the HashMap: " + map.size());

        //8-----> Clearing the HashMap
        map.clear();
    }   

    public static void treemap(){
        TreeMap<String, Integer> map=new TreeMap<String, Integer>();
        //1-----> Adding key-value pairs to the TreeMap
        map.put("A", 1);
        map.put("B", 2);
        map.put("C", 3);
        map.put("D", 4);

        //2-----> Displaying the TreeMap
        System.out.println("TreeMap: " + map);

        //3-----> Accessing a value by key from the TreeMap
        System.out.println("Value for key 'B': " + map.get("B"));

        //4-----> Updating a value in the TreeMap
        map.put("B", 20);
        System.out.println("After updating key 'B': " + map);

        //5-----> Removing a key-value pair from the TreeMap
        map.remove("C");
        System.out.println("After removing key 'C': " + map);

        //6-----> Iterating through the TreeMap
        System.out.println("Iterating through the TreeMap:");
        for(Map.Entry<String, Integer> entry : map.entrySet()){
            System.out.println("Key: " + entry.getKey() + ", Value: " + entry.getValue());
        }

        //7-----> Size of the TreeMap
        System.out.println("Size of the TreeMap: " + map.size());

        //8-----> Clearing the TreeMap
        map.clear();
    }   

    public static void linkedhashmap(){
        LinkedHashMap<String, String> map=new LinkedHashMap<String, String>();
        //1-----> Adding key-value pairs to the LinkedHashMap
        map.put("Name", "Alice");
        map.put("City", "New York");
        map.put("Country", "USA");
        map.put("Occupation", "Engineer");

        //2-----> Displaying the LinkedHashMap
        System.out.println("LinkedHashMap: " + map);

        //3-----> Accessing a value by key from the LinkedHashMap
        System.out.println("Value for key 'City': " + map.get("City"));

        //4-----> Updating a value in the LinkedHashMap
        map.put("City", "Los Angeles");
        System.out.println("After updating key 'City': " + map);

        //5-----> Removing a key-value pair from the LinkedHashMap
        map.remove("Country");
        System.out.println("After removing key 'Country': " + map);

        //6-----> Iterating through the LinkedHashMap
        System.out.println("Iterating through the LinkedHashMap:");
        for(Map.Entry<String, String> entry : map.entrySet()){
            System.out.println("Key: " + entry.getKey() + ", Value: " + entry.getValue());
        }

        //7-----> Size of the LinkedHashMap
        System.out.println("Size of the LinkedHashMap: " + map.size());

        //8-----> Clearing the LinkedHashMap
        map.clear();
    }   
```
