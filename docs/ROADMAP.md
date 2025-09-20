public class BetterOptionsProject {

    static class BusinessOpportunities {
        String[] opportunities = {"Incubation", "Linkages", "Franchising"};

        void display() {
            System.out.println("Business Opportunities:");
            for (String o : opportunities) {
                System.out.println("- " + o);
            }
        }
    }

    static class FundingPrograms {
        String[] programs = {"Seed Grants", "Microloans", "Investor Showcases"};

        void display() {
            System.out.println("Funding Programs:");
            for (String p : programs) {
                System.out.println("- " + p);
            }
        }
    }

    static class ImpactOutcomes {
        int businesses;
        int youthTrained;
        double revenueGrowthPercent;

        ImpactOutcomes(int b, int y, double r) {
            businesses = b;
            youthTrained = y;
            revenueGrowthPercent = r;
        }
        
        void display() {
            System.out.println("Impact & Outcomes:");
            System.out.println("- " + businesses + " Businesses");
            System.out.println("- " + youthTrained + " Youth Trained");
            System.out.println("- " + revenueGrowthPercent + "% Revenue Growth");
        }
    }

    static class Advertising {
        String[] methods = {"Radio", "Digital Directory", "Social Media"};

        void display() {
            System.out.println("Business Advertising:");
            for (String m : methods) {
                System.out.println("- " + m);
            }
        }
    }

    static class YouthEmpowerment {
        String[] trainings = {"Training", "Digital Skills", "Mentorship"};

        void display() {
            System.out.println("Youth Empowerment:");
            for (String t : trainings) {
                System.out.println("- " + t);
            }
        }
    }

    public static void main(String[] args) {
        System.out.println("Better Options for All (Mukurweini Pilot Project)\n");

        BusinessOpportunities bo = new BusinessOpportunities();
        FundingPrograms fp = new FundingPrograms();
        ImpactOutcomes io = new ImpactOutcomes(150, 600, 30.0);
        Advertising ad = new Advertising();
        YouthEmpowerment ye = new YouthEmpowerment();

        bo.display();
        System.out.println();

        fp.display();
        System.out.println();

        io.display();
        System.out.println();

        ad.display();
        System.out.println();

        ye.display();
    }
}
