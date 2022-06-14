# CV for RSSchool

# Aleksandr Petushenko - Junior Java Developer

![Profile photo](https://media-exp2.licdn.com/dms/image/D4D35AQHGPQvHlWLOOA/profile-framedphoto-shrink_200_200/0/1640002003303?e=1655776800&v=beta&t=sPJPaexsTQLU5zr_0D931Se7dpu1NPiVAUKsndFnPa4 "My photo")

## Contacts
    * Mail: aleksandr.petushenko1.gmail.com
    * Phone: +375447610488
    * LinkedIn: https://www.linkedin.com/in/moonbl4/

## Summary
    I study Java on my own. Graduated from Java EE courses and received an offer. But because of the war, it was canceled. Now I decided to study JS in order to independently make applications from beginning to end.

## Skills
    Java, Spring Framework, Spring Boot, ACID, SQL, NoSQL, Git, Maven, Gradle, HTML/CSS.

## Code Examples
    
    public class Solution {

        public static String camelCase(String str) {
            final StringBuilder sb = new StringBuilder();
            boolean isPreviousCharSpace = false;

            for (int i = 0; i < str.length(); i++) {
                final char current = str.charAt(i);

                if ((i == 0 || isPreviousCharSpace) && !Character.isWhitespace(current)) {
                    sb.append(Character.toUpperCase(current));
                    isPreviousCharSpace = false;
                } else if (Character.isWhitespace(current)) {
                    isPreviousCharSpace = true;
                } else {
                    sb.append(current);
                }
            }
            return sb.toString();
        }
    }

## Work experience
    I took courses at the company for half a year, did educational projects.

## Education
    Belarusian State University of Transport

## English
    Pre-Intermediate