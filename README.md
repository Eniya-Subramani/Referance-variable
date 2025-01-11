# Referance-variable
class Student {
int id;
String name;
}
Class TestStudent {
Public static void main(String[] args) {

Student s1 = new Student();
Student s2 = new Student();
s1.id = 101;
s1.name = &quot;Sonoo&quot;;
s2.id = 102;
s2.name = &quot;Amit&quot;;
System.out.println(&quot;Student 1: &quot; + s1.name);
System.out.println(&quot;Student 2: &quot; + s2.name);
}
}
OUTPUT:
Student 1: Sonoo
Student 2: Amit
