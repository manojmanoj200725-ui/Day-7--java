# Day-7--java
#Java 7(Calculator)

import java.util.Scanner;

class calc
{

    public static void main(String[] args)
    {
    
        int a,b,choice;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a first Number:");
        a = sc.nextInt();
        System.out.println("Enetr second number:");
        b = sc.nextInt();
        
        System.out.println("1.Addition=");
        System.out.println("2.Subtraction=");
        System.out.println("3.Multiplication=");
        System.out.println("4.Division=");
        choice = sc.nextInt();
        switch(choice)                                                 //Run by Bluej compiler
        {
            case 1:
                System.out.println("Addition="+(a+b));
                break;
                case 2:
                    System.out.println("subtraction="+(a-b));                        
                    break;
                    case 3:
                        System.out.println("Multiplie="+(a*b));
                        break;
                        case 4:
                            System.out.println("Division="+(a/b));
                            break;
                            default:
                                System.out.println("Invalid:");
                            }
                        }
                    }
                            
        
