public class AssignC6 {

    public static void main(String[] args) {
        // Display converted table of feet to meters
        System.out.println("FootToMeter");
        for (double feet = 1.0, meters = 20.0; feet <= 10.0; feet++, meters += 5) {
            System.out.println(feet + "\t" + footToMeter(feet) + "\t/\t" + meters + "\t" + meterToFoot(meters));
        }
    }

    /** Convert from feet to meters */
    public static double footToMeter(double foot) {
        return 0.305 * foot;
    }

    /** Convert from meters to feet */
    public static double meterToFoot(double meter) {
        return 3.279 * meter;
        
FootToMeter
1.0     0.305   /       20.0    65.58
2.0     0.61    /       25.0    81.975
3.0     0.915   /       30.0    98.37
4.0     1.22    /       35.0    114.765
5.0     1.525   /       40.0    131.16
6.0     1.83    /       45.0    147.555
7.0     2.135   /       50.0    163.95
8.0     2.44    /       55.0    180.345
9.0     2.745   /       60.0    196.74
10.0    3.05    /       65.0    213.135
