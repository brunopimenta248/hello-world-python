# Hello World 
This is a simple Python script that prints "Hello, World!" to the console. This script serves as a classic example of a minimal Python program, often used as a starting point for beginners to learn the syntax of the language.

``` python
def main():
    message = "Hello, World!"
    print(message)
    
    with open("output.txt", "w") as file:
        file.write(message)
    
if __name__ == "__main__":
    main()
```
