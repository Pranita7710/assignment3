# assignment3
basic if else assignments
Q1)nuber is positve or negative 
public class basic3 {
    public static void main(String args[]){
        //int num=5;
        int num=-9;
        if(num>0){
            System.out.println( num + "is positive");
        }
        else if(num<0){
            System.out.println(num + "is negative");
        }
        else{
            System.out.println(num + "is zero");
        }
    }
}

output:-9is negative
        5 is positive

Q2)number is even or odd
public class basic3 {
    public static void main(String args[]){
        //int num=13;
        int num=8;
       if(num%2==0){
            System.out.println( num + "is even");
        }
        else{
            System.out.println(num + "is odd");
        }
    }
}

output:13is odd
       8is even

Q3)number is greater than 10 or less than 10
public class basic3 {
    public static void main(String args[]){
        int num=13;
        //int num=8;
       if(num>10){
            System.out.println( num + "is greater than 10");
        }
        else if(num<10){
            System.out.println( num + "is less than 10");
        }
        else{
            System.out.println(num + "is 10");
        }
    }
}

output:8is less than 10
       13is greater than 10

Q4) given character is in uppercase or in lowercase
public class basic3 {
    public static void main(String args[]){
        //char ch='a';
        char ch='A';
        
       if(ch>=97&&ch<122){
        System.out.println(ch +" is lowercase");
       }else if(ch>=65&&ch<90){
        System.out.println(ch +" is uppercase");
       }else{
        System.out.println(ch +"invalid character");
       }
    }
}

output:A is uppercase
       a is lowercase


Q5)given number is divisible by 7 or not
public class basic3 {
    public static void main(String args[]){
        //int x=105;
        int x=-31;
       if(x%7==0){
        System.out.println(x +" is divisble by 7");
       }else{
        System.out.println(x+" is not divisible by 7");
       }
    }
}

output:105 is divisble by 7
       -31 is not divisible by 7


Q6)given number is divisible by 3 or 7
public class basic3 {
    public static void main(String args[]){
       //int x=28;
       //int x=15;
       int x=20;
       if(x%3==0){
        System.out.println(x +" is divisble by 3");
       }else if(x%7==0){
        System.out.println(x+" is  divisible by 7");
        }else{
            System.out.println(x+" is not divisible by 3 or 7");
        }
    }     
}

output:28 is  divisible by 7
       15 is divisble by 3
       20 is not divisible by 3 or 7


Q7)
public class basic3 {
    public static void main(String args[]){
       //int x=15;
       int x=10;
        if(x%2==0 && x%5==0 && x%10==0 ){
            System.out.println(x+" is divisible by 2,5 and 10");
        }else{
            System.out.println(x+" is not divisible by 2,5 and10");
        }
    }     
}

output:15 is not divisible by 2,5 and10
       10 is divisible by 2,5 and 10
Q8)
public class basic3 {
    public static void main(String args[]){
       //int x=1;
       // int y=2;
       int x=9;
       int y=5;
        if(x>y){
            System.out.println(x+" is greter than"+y);
        }else{
            System.out.println(y+" is greter than "+x);
        }

    }     
}

output:2 is greter than 1
       9 is greter than 5
