https://replit.com/@yinonadam/yudim#Main.java
// שאלה 1
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       System.out.println("Enter a number");
//       int x;
//       x=scan.nextInt();
//       if(x>0)
//         System.out.println("The number is positive");
//       else
//         System.out.println("The number is negative");


//     }
// }

//שאלה 2
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       System.out.println("Enter a number");
//       int x;
//       System.out.println("Enter a number again");
//       int y;
//       x=scan.nextInt();
//       y=scan.nextInt();
//       if(x>y)
//         System.out.println(x+" The number is the biggest");
//       else
//         System.out.println(y+" The number is the biggest");

//     }
// }
//שאלה 3
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       System.out.println("enter player1:");
//       string player1=scan.next();
//       System.out.println("enter player2:");
//       string player2=scan.next();
//       System.out.println("enter x1:");
//       int x1=scan.nextInt();
//       System.out.println("enter x2:");
//       int x2=scan.nextInt();
//       System.out.println("enter v1:");
//       int v1=scan.nextInt();
//       System.out.println("enter v2:");
//       int v2=scan.nextInt();
//       Double t1=(v1/x1);
//       Double t2=(v2/x2);
//       if(t1>t2)
//        System.out.println(player1+" wins");
//       else
//         System.out.println(player2+" wins");
//     }
// }
//שאלה 4
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       int grade1,grade2,grade3,Avg;

//       System.out.println("Enter a number");
//       grade1=scan.nextInt();
//       System.out.println("Enter a number again");
//       grade2=scan.nextInt();
//       System.out.println("Enter a number");
//       grade3=scan.nextInt();


//       Avg=(grade1+grade2+grade3);     
//       System.out.println("The average is: "+Avg/3);
//     }
// }
//שאלה 5
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       int num1,num2,num3;

//       System.out.println("Enter a number");
//       num1=scan.nextInt();
//       System.out.println("Enter a number again");
//       num2=scan.nextInt();
//       System.out.println("Enter a number");
//       num3=scan.nextInt();

//       if (num1<num2 && num1<num3)
//         System.out.println(num1+" is the small one");
//       if (num2<num1 && num2<num3)
//         System.out.println(num2+" is the small one");
//       else
//         System.out.println(num3+" is the small one");
//     }
// }
//שאלה 6
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       int x1,x2,y1,y2;

//       System.out.println("Enter a number");
//       x1=scan.nextInt();
//       System.out.println("Enter a number again");
//       y1=scan.nextInt();
//       System.out.println("Enter a number");
//       x2=scan.nextInt();
//       System.out.println("Enter a number again");
//       y2=scan.nextInt();

//       double distance=Math.sqrt(Math.pow(x2-x1,2)+Math.pow(y2-y1,2));
//       System.out.println("The distance between the two points is "+s);

//     }
// }
//שאלה 7
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       System.out.print("Enter the first term of the series: ");
//       double firstTerm = scan.nextDouble();

//       System.out.print("Enter the common difference of the series: ");
//       double commonDifference = scan.nextDouble();

//       double fifthTerm = firstTerm + 4 * commonDifference;
//       double tenthTerm = firstTerm + 9 * commonDifference;

//       System.out.println("The fifth term of the series is: " + fifthTerm);
//       System.out.println("The tenth term of the series is: " + tenthTerm);


//     }
// }
//שאלה 8
// import java.util.Scanner;
// public class IceCreamShop {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);
//         System.out.print("Enter the number of ice creams you want to buy: ");
//         int numberOfIceCreams = scanner.nextInt();
//         int price = calculatePrice(numberOfIceCreams);
//         System.out.println("The minimum price to pay is: " + price + " shekels.");
//         scanner.close();
//     }
//     private static int calculatePrice(int numberOfIceCreams) {
//         final int PRICE_PER_SINGLE = 120;
//         final int PRICE_PER_CARTON = 500;
//         int cartonCount = numberOfIceCreams / 54;
//         int remainingIceCreams = numberOfIceCreams % 54;
//         int totalPrice = cartonCount * PRICE_PER_CARTON + remainingIceCreams * PRICE_PER_SINGLE;
//         if (cartonCount > 2) {
//             System.out.println("Cannot order more than 108 ice creams in one purchase.");
//             System.exit(0);
//         }

//         return totalPrice;
//     }
// }

// שאלה 9
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//       Scanner scan= new Scanner(System.in);
//       System.out.print("Enter your first name and last name: ");
//       String fullName = scan.nextLine();

//       System.out.print("Enter your school name: ");
//       String schoolName = scan.nextLine();

//       System.out.print("Enter the number of study subjects: ");
//       int numberOfSubjects = scan.nextInt();

//       System.out.println("My name is " + fullName + ".");
//       System.out.println("My school is " + schoolName + ".");
//       System.out.println("The number of subjects I study is " + numberOfSubjects + ".");

//     }
// }
//שאלה 10
// import java.util.Scanner;
// public class Main {
//     public static void main(String[] args) {
//         Scanner scan = new Scanner(System.in);
//         System.out.print("Enter a three digit number: ");
//         int num = scan.nextInt();
//         int hundreds = num / 100;
//         int tens = (num % 100) / 10;
//         int unit = num % 10;
//         int sum = thousands + hundreds + tens + unit;
//         System.out.println("the sum of this number digit id :"+ sum);
//     }
// }
