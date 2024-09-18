# Grokking the Coding Interview in C\#

This repository contains my C# solutions to the problems from **Grokking the Coding Interview**. Each solution includes explanations to help you understand the problem-solving approach.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running Individual Tests](#running-individual-tests)
- [Solutions](#solutions)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Introduction

The goal of this project is to provide solutions to Grokking The Coding Interview problems using C#. The problems will include explanations, and deepen your understanding of algorithms and data structures, which are essential for technical interviews.

## Getting Started

Follow these instructions to set up the project on your local machine for development and testing.

### Prerequisites

- **Visual Studio** (2019 or later recommended)
- **.NET Framework** (compatible with your version of Visual Studio)
- Basic knowledge of C# programming

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/grokking-the-coding-interview-csharp.git
   ```

2. **Open the solution in Visual Studio:** 
- Navigate to the cloned directory.
- Open the `.sln` file with Visual Studio.

3. **Restore NuGet packages:**
- Visual Studio should automatically restore any necessary packages.
- If not, go to `Tools` > `NuGet Package Manager` > `Package Manager Console` and run:
  ```PowerShell
    Update-Package -Reinstall
  ```  
## Usage
### Running Individual Tests
You can run individual tests to check each solution:
- Open **Test Explorer** in Visual Studio (`Test` > `Test Explorer`).
- To run all tests, press `Ctrl + R`, then `A`.
- To run a specific test:
  - Select the test in **Test Explorer**.
  - Press `Ctrl + R`, then `T`, or right-click and select **Run Selected Tests**.

## Solutions
Each folder in the repository corresponds to a specific topic or problem set. For each problem set, you'll find:
- **Solution Code:** The C# implementation of the problem.
- **Explanation:** Comments and notes explaining the logic and approach.
- **Unit Tests:** Test cases to verify the solution's correctness.

Feel free to explore the code and run the tests to see how each solution works.

## Contributing
Contributions are welcome! If you'd like to improve existing solutions or add new ones:
1. **Fork the repository.**
2. **Create a new branch:**
```bash
git checkout -b feature/your-feature-name
```
3. **Commit your changes:**
```bash
git commit -m 'Add new solution for problem X'
```
4. **Push to the branch:**
```bash
git push origin feature/your-feature-name
```
5. **Open a Pull Request.**

## Acknowledgments
- **Design Gurus** for the **Grokking the Coding Interview** course.
- The developer community for support and shared knowledge.

