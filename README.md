#GradeCalculator


import java.util.Scanner;

public class GradeCalculator {
    public static void main(String[]args){

    Scanner input = new Scanner (System.in);

    //input homework
    System.out.print("Enter Homework Score:  ");
    //creating the variable for homework
    double homework = input.nextDouble();

    //input codelab
    System.out.print("Enter CodeLab Score:    ");
    //creating the variable for codelab
    double codelab = input.nextDouble();

    //input midterm1
    System.out.print("Enter Midterm 1 Score:    ");
    //creating the variable for midterm1
    double midterm1 = input.nextDouble();

    //input midterm2
    System.out.print("Enter Midterm 2 Score:    ");
    //creating the variable for midterm2
    double midterm2 = input.nextDouble();

    //input final
    System.out.print("Enter Final Exam Score:      ");
    //creating the variable for final
    double finaltest = input.nextDouble();

    //identifying the vatiable to collect the sum of all
    double totalscore = homework + codelab + midterm1 + midterm2 + finaltest;
    //going to outprint the final result
    System.out.println(" The toal score is " + totalscore);

    }
}
