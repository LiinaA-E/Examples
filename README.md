# New-Learning-Repository
Learning to know more about Github

## Heading
Using "##" for heading

## JAVA code
```java
import java.util.Scanner;

public class LoginApplication {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        final String STORED_USERNAME = "user123";
        final String STORED_PASSWORD = "pass123";

        System.out.print("input your username: ");
        String username = scanner.nextLine();

        System.out.print("input your password: ");
        String password = scanner.nextLine();

        if (username.equals(STORED_USERNAME) && password.equals(STORED_PASSWORD)) {
            System.out.println("you have access");
        } else {
            System.out.println("username or password is invalid");
        }

        scanner.close();
    }
}
```

## Python code

```py
STORED_USERNAME ='user123'
STORED_PASSWORD = 'pass123'

username = input('Enter your username: ')
password = input('Enter your password ')

# AND OR

if STORED_USERNAME == username and STORED_PASSWORD == password: 
  print('access ganted!')
else:
  print('access denied!')
```
