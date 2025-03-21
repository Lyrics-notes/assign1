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
        
