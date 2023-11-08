import java.until.Random; 
 public class Rockpaperscissors{


 public static void main(String[]args){
String[]rps={"r" , "p" , "s"};
String computerMOVE = rps[new Random().nextInt(rps.lenght)];
Scanner scanner = new Scanner(System.in);
String playMove; 




while(true){
System.out.println("Please  enter your move(r,p or s)");
 playerMove = scanner.nextline();
if(playerMove.equals("r")|| playerMove.equals("p")|| playerMove.equals("s")){
    break;
}
System.out.println(playerMove + "is not valid move.");
}

System.out.println( "Computer played:"+ computerMove);

if(playerMove.equals(computerMove)){
    System.out.println("The game was a tie");
}
else if (playerMove.equals("r")){
    if(computerMove.equals("p")){
        System.out.println("You Lose");
         
    } else if (computerMove.equals("s")){
        System.out.println("You Win ");
}
}

else if (playerMove.equals("p")){
    if(computerMove.equals("r")){
        System.out.println("You Win");
        
         } else if(computerMove.equals("s")){
            System.out.println("You Lose");
          
        }
}
else if (playerMove.equals("s")){
    if(computerMove.equals("p")){
        System.out.println("You Win");

    } else if (computerMove.equals("r")) {
        System.out.println("You loose");
        }
            }
            


