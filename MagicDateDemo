import java.util.*;
class MagicDateDemo extends MagicDate
{
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        MagicDateDemo res = new MagicDateDemo();
       
        //set month
        System.out.println("Please Enter Month");
        res.setMonth(scan.nextInt());
        
        //error check for month 
        if( month<=0 || month>12){
            System.out.println("Invalid Month");
            System.exit(0);
        }
        
        //set day
        System.out.println("Please Enter Day");
        res.setDay(scan.nextInt());
        
        //error check for months with 31 days 
        if((month == 01 || month == 03 || month == 05 || month == 07 || month == 8 || month == 10 || month == 12) && day > 31){
            
            System.out.println("Invalid Date");
            System.exit(0);
        }
        
        //error check for months with 30 days
        if ((month == 04 || month == 06 || month == 9 || month == 11) && day > 30){
             System.out.println("Invalid Date");
            System.exit(0);
        }
        //error check for valid Feb date
        if(month == 2 && day>28){
            System.out.println("Invalid Date");
            System.exit(0);
        }
 
        //error check for valid month and day 
          if( month==2 && day==29){
            System.out.println("Do not enter Feb 29th");
            System.exit(0);
        }
        
        //set year
        System.out.println("Please Enter Year in two digit format");
        res.setYear(scan.nextInt());
        
        //error check year
     if( year<=0 || year>99){
         System.out.println("Invalid Year");
            System.exit(0);
        }
        
        //result returns  is or is not Magic Date
        System.out.println(isMagicDate());
    }
}
