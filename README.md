# Student

public class Student {
    int id;
    Student()
    {
       // this(10);
        System.out.println("constructor 1");
    }
   /* void disp()
    {
        System.out.println("I am from disp");
    }

   Student(int id)
   {
       this();
       System.out.println("constructor 2");

   }
   Student(int x,int y)
   {
       this(10);
       System.out.println("constructor 3");

   }


   Student(int x)
   {
       System.out.println("Parameterised const");
   }

    public Student() {

    }

    void disp()
   {
       System.out.println("I am from disp");
   }
}

# Main

public class Main1 {
    public static void main(String[] args) {
        Student s1=new Student();
        s1.disp();
        new Student().disp();
        Student s1;
        s1=new Student();
        new Student();
        new Student();
        new Student(10,20);
        Student s1=new Student();
        s1.disp();
        Student s2=new Student();
        s2.disp();
    }
}

