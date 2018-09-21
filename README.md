# String-assignments
Bad
package stringAssignments;

import java.util.Scanner;

public class Bad {
    public static void main(String[] args) {
		
    	Scanner nany =new Scanner(System.in);
    	System.out.println("Enter please any word");
    	String word =nany.next();
    	
    	if(word.length()>=4 && word.contains("bad")==true) {
    		System.out.println("true");
    	} else {
    		System.out.println("invalid entry");
    	}
    	nany.close();
	}
}
