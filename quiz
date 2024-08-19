import java.util.HashMap;
import java.util.Map;
import java.util.Scanner;
import java.util.Random;

public class Main {

    public static void main(String[] args) {
        Map<String, String> statesAndCapitals = new HashMap<>();
        statesAndCapitals.put("Andhra Pradesh", "Amaravati");
        statesAndCapitals.put("Arunachal Pradesh", "Itanagar");
        statesAndCapitals.put("Assam", "Dispur");
        statesAndCapitals.put("Bihar", "Patna");
        statesAndCapitals.put("Chhattisgarh", "Raipur");
        statesAndCapitals.put("Goa", "Panaji");
        statesAndCapitals.put("Gujarat", "Gandhinagar");
        statesAndCapitals.put("Haryana", "Chandigarh");
        statesAndCapitals.put("Himachal Pradesh", "Shimla");
        statesAndCapitals.put("Jharkhand", "Ranchi");
        statesAndCapitals.put("Karnataka", "Bengaluru");
        statesAndCapitals.put("Kerala", "Thiruvananthapuram");
        statesAndCapitals.put("Madhya Pradesh", "Bhopal");
        statesAndCapitals.put("Maharashtra", "Mumbai");
        statesAndCapitals.put("Manipur", "Imphal");
        statesAndCapitals.put("Meghalaya", "Shillong");
        statesAndCapitals.put("Mizoram", "Aizawl");
        statesAndCapitals.put("Nagaland", "Kohima");
        statesAndCapitals.put("Odisha", "Bhubaneswar");
        statesAndCapitals.put("Punjab", "Chandigarh");
        statesAndCapitals.put("Rajasthan", "Jaipur");
        statesAndCapitals.put("Sikkim", "Gangtok");
        statesAndCapitals.put("Tamil Nadu", "Chennai");
        statesAndCapitals.put("Telangana", "Hyderabad");
        statesAndCapitals.put("Tripura", "Agartala");
        statesAndCapitals.put("Uttar Pradesh", "Lucknow");
        statesAndCapitals.put("Uttarakhand", "Dehradun");
        statesAndCapitals.put("West Bengal", "Kolkata");

        Scanner scanner = new Scanner(System.in);
        Random random = new Random();
        String[] states = statesAndCapitals.keySet().toArray(new String[0]);
        int score = 0;

        for (int i = 0; i < 5; i++) {
            String randomState = states[random.nextInt(states.length)];
            System.out.println("What is the capital of " + randomState + "?");
            String answer = scanner.nextLine().trim();

            if (answer.equalsIgnoreCase(statesAndCapitals.get(randomState))) {
                System.out.println("Correct!");
                score++;
            } else {
                System.out.println("Wrong! The correct answer is " + statesAndCapitals.get(randomState));
            }
        }

        // Final score
        System.out.println("Quiz completed! Your score is " + score + "/5.");
        scanner.close();
    }
}
