# my first program percentage-calculator-

    import java.util.Scanner;

    class percenatagecalculator{

    public static void main(String[] args) {
        Scanner scn = new Scanner(System.in);
        
        System.out.println(" Each Marks for Each Subject ");
        System.out.println(" physics : ");
        double physicsMarks = scn.nextDouble();

        System.out.println( " chemsitry : ");
        double chemistryMarks = scn.nextDouble();

        System.out.println(" maths : ");
        double mathsMarks = scn.nextDouble();

        System.out.println(" english : ");
        double englishMarks = scn.nextDouble();

        System.out.println(" hindi : ");
        double hindiMarks = scn.nextDouble();

        double totalMarks = physicsMarks+chemistryMarks+mathsMarks+englishMarks+hindiMarks;
        double percentage = (totalMarks/500)*100;

        System.out.println(" total marks obtain: "+ totalMarks);
        System.out.println(" percentage: " +percentage + "%");
        if (percentage < 33){
            System.out.println(" fail");
        }else {
            System.out.println(" pass");
        }

    }
}
