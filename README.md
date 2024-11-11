# Java

simple and Easy to start with
Java is a high-level, object-oriented programming language 
that's used to create applications for
mobile devices,
web apps, enterprise software, and more.

# Hello world

class jenil

{
    
    public static void main(String args[])
    
    {
        System.out.println("hello world");
    }
}


# Datatypes


import java.util.Scanner;

class datatypes

{
    
    public static void main(String args[])
    {
        int age;
        long sal;
        float amt;
        double gst;
        String name;
        char letter;

        Scanner scr=new Scanner(System.in); //scanner is used for taking unputs from user and "new" is the keyword
        Scanner scr1=new Scanner(System.in);

        System.out.println("enter the age");
        age=scr.nextInt();
        System.out.println("age is "+age);

        System.out.println("enter thr sal");
        sal= scr.nextLong();
        System.out.println("sal is "+sal);

        System.out.println("enter the amt");
        amt=scr.nextFloat();
        System.out.println("amt is "+amt);

        System.out.println("enter the gst");
        gst=scr.nextDouble();
        System.out.println("gst is "+gst);

        System.out.println("enter the name");
        name=scr1.nextLine();
        System.out.println("name is "+name);

        System.out.println("enter the letter");
        letter=scr1.next().charAt(0);
        System.out.println("letter is "+letter);


    }


}

