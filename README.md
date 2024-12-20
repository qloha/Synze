
  

# Synze

  

### Synze is a simple interpreted programming language implemented in C++. It provides basic programming constructs including variable declarations, mathematical operations, and string manipulation.

#### Virustotal flags this as malicious, and if you don't want to download, honestly thats ok. However if you do decide to download this, I can assure you that it is not a virus whatsoever.
#### When you open it after you download it, Microsoft Defender will have a popup saying that it is a virus. You do not have to proceed, but if you do, click more details and then a run anyway button will appear in the bottom right corner.
  

## 🌟 Features

  

- Variable declarations (string, number, boolean)

- Basic arithmetic operations (+, -, *, /)

- String concatenation

- File execution support (.synze files)

- Real-time command interpretation

- Error handling and reporting

  

## 🛠️ Building

  

To build Synze, you need:

- CMake (3.5.0 or higher)

- C++ compiler with C++11 support

  

> mkdir build

> cd build

> cmake ..

> cmake --build .

  

## 🚀 Usage

  

After building, you can run Synze in two ways:

  

1. Interactive Mode:

> ./Synze

  

2. File Execution:

# ⌨️ In the interactive mode

```
>> run example.synze
```
  

## 📜 Syntax

  

### Variable Declaration

> variable [name] = [value]

  

### Output

> send [expression]

  

### File Execution

> run [filename.synze]

  

### Exit

> exit

  

## 🧪 Examples

  

### Declaring a Variable

> variable message = "Hello, World!"

> send message

  

### Performing Arithmetic

> send 5 + 3 * 2

  

### String Concatenation

> variable name = "John"

> send "Hello, " + name

  

### Boolean Variable

> variable isActive = true

> send isActive

  

### File Execution Example

Create a file called example.synze:

> variable message = "File execution successful!"

> send message

  

Then, in interactive mode, run the file:

```
>> run example.synze
```

  

## 📖 License

  

>     This project is open source and available under the [MIT License](https://mitlicense.org/).