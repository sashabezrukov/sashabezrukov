- 👋 Hi, I’m @sashabezrukov
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sashabezrukov/sashabezrukov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Програма для знаходження найбільшого числа в масиві на мові Java:
java
Copy code
public class MaximumNumber {
    public static void main(String[] args) {
        int[] numbers = {5, 10, 2, 8, 3};
        int max = numbers[0];

        for (int i = 1; i < numbers.length; i++) {
            if (numbers[i] > max) {
                max = numbers[i];
            }
        }

        System.out.println("The maximum number is: " + max);
    }
}
