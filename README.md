class employee{
    String name,city;
    int age;
    
    public void display(){
        System.out.println(name);
        System.out.println(age);
        System.out.println(city);
    }
}
public class Main{
    public static void main(String[] args){
        employee e= new employee();
        e.name="The name is saurab";
        e.age=23;
        e.city="The city is chennai";
        e.display();

    }
}
