RollDice

import java.util.Random;
public class Dice {

  public static void main (String [] args)
  {
  	int numberOfDice;
  		Random rand = new Random();
  		numberOfDice = 1 + rand.nextInt(6);
  		System.out.printf("%d ", numberOfDice);
  	
  }

  
}

========
