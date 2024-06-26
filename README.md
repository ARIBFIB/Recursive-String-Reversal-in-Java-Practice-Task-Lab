# Recursive-String-Reversal-in-Java-Practice-Task-Lab
Practice Task 4:  Implement a recursive function to reverse a string. For example, given the input "hello", the function should return "olleh" 

# String Reversal


## Recursive String Reversal in Java
![image](https://github.com/ARIBFIB/Recursive-String-Reversal-in-Java-Practice-Task-Lab/assets/125716994/b40f5b57-fab1-4266-ac1f-20071ad481c3)

This project demonstrates a recursive function that takes a string as input and returns the reversed version of that string.

### Example

```java
public class StringReversal {
    public static String reverseString(String input) {
        if (input.isEmpty()) {
            return input;
        }
        return reverseString(input.substring(1)) + input.charAt(0);
    }

    public static void main(String[] args) {
        String input = "hello";
        String reversed = reverseString(input);
        System.out.println("Original string: " + input);
        System.out.println("Reversed string: " + reversed);
    }
}
```

This will output:

```
Original string: hello
Reversed string: olleh
```
# Another Output
![image](https://github.com/ARIBFIB/Recursive-String-Reversal-in-Java-Practice-Task-Lab/assets/125716994/f4213fce-fcf0-4f95-9737-91a8f7eefd73)

### How it Works

The `reverseString()` function uses recursion to reverse the input string. Here's how it works:

1. If the input string is empty, the function simply returns the empty string.
2. Otherwise, the function recursively calls itself with the substring of the input string starting from the second character (i.e., `input.substring(1)`).
3. The function then concatenates the result of the recursive call with the first character of the input string (`input.charAt(0)`).

This process continues until the base case (an empty string) is reached, at which point the function starts to unwind the recursive calls and build the reversed string.

### GitHub README

Here's an example of a GitHub README for this project:

# String Reversal


> **Reverse a string using recursion in Java**

## 🚀 About the Project

This project demonstrates a recursive function that takes a string as input and returns the reversed version of that string.

## 🛠️ Features

- Recursive implementation of string reversal
- Easy-to-understand code with comments
- Efficient and elegant solution

## 🔧 Installation and Usage

1. Clone the repository:
   ```
   [git clone https://github.com/your-username/string-reversal.git](https://github.com/ARIBFIB/Recursive-String-Reversal-in-Java-Practice-Task-Lab.git)
   ```
2. Compile and run the `StringReversal` class:
   ```
   cd string-reversal
   javac StringReversal.java
   java StringReversal
   ```

## 🤝 Contributing

Contributions are always welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Developer

- [Abdul Rehman Irfan]([https://github.com/ARIBFIB])

[String Reversal Icon]: https://github.com/your-username/string-reversal/blob/main/assets/string-reversal-icon.png

In this example, the GitHub README includes the following elements:

- A main image for the String Reversal project
- A beautiful description of the project
- A section explaining how the recursive string reversal function works
- Instructions for installation and usage
- A contribution section
- A license section
- Information about the author(s)

The README also uses various fonts, styles, and icons to enhance the visual appeal and organization of the content.
