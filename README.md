# horoscoperFinder
import java.util.Scanner;

public class HoroscopeFinder {
    public static void main(String[] args) {
        int m, d;
        Scanner input = new Scanner(System.in);
        System.out.println("What Is Your Birth Mont?");
        m = input.nextInt();
        System.out.println("What Is Your Birth Day");
        d = input.nextInt();
        if ((m >= 1 && m <= 12) && (d >= 1 && d <= 31)) {
            if (m == 3) {
                if (d >= 21)
                    System.out.println("Aries");
                else if (d <= 20) {
                    System.out.println("Pisces");
                } else {
                    System.out.println("Wrong Entry");

                }
            }
            if (m == 4) {
                if (d >= 21) {
                    System.out.println("Taurus");
                } else if (d <= 20) {
                    System.out.println("Aries");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 5) {
                if (d >= 22) {
                    System.out.println("Gemini");
                } else if (d <= 21) {
                    System.out.println("Taurus");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 6) {
                if (d >= 23) {
                    System.out.println("Cancer");
                } else if (d <= 22) {
                    System.out.println("Gemini");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 7) {
                if (d >= 23) {
                    System.out.println("Leo");
                } else if (d <= 22) {
                    System.out.println("Cancer");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 8) {
                if (d >= 23) {
                    System.out.println("Virgo");
                } else if (d <= 22) {
                    System.out.println("Leo");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 9) {
                if (d >= 23) {
                    System.out.println("Libra");
                } else if (d <= 22) {
                    System.out.println("Virgo");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 10) {
                if (d >= 23) {
                    System.out.println("Scorpio");
                } else if (d <= 22) {
                    System.out.println("Libra");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 11) {
                if (d >= 22) {
                    System.out.println("Sagittarius");
                } else if (d <= 22) {
                    System.out.println("Scorpio");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 12) {
                if (d >= 22) {
                    System.out.println("Capricorn");
                } else if (d <= 21) {
                    System.out.println("Sagittarius");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 1) {
                if (d >= 22) {
                    System.out.println("Aquarius");
                } else if (d <= 21) {
                    System.out.println("Capricorn");
                } else {
                    System.out.println("Wrong Entry");
                }
            }
            if (m == 2) {
                if (d >= 20) {
                    System.out.println("Pisces");
                } else if (d <= 19) {
                    System.out.println("Aquarius");
                } else {
                    System.out.println("Wrong Entry");
                }
            }

        } else {
            System.out.println("Wrong Entry");
        }
    }
}
