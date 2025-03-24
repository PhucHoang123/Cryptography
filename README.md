# Cryptography

This is a C# console application that demonstrates the use of the **Hill Cipher**, a classical cryptographic algorithm, using **2x2 matrices**. The application supports both **encryption and decryption** of alphabetic text under **modulo 26 and 29 arithmetic**, enabling a layered encryption strategy.

## 🔐 Features
- Hill Cipher encryption and decryption
- Uses two sets of matrices for dual-layer security
- Supports extended characters: space (`' '`), question mark (`'?'`), and exclamation mark (`'!'`) under mod 29
- Fully modular and reusable cryptographic methods

## 🛠 Technologies Used
- **C#** (.NET)
- **MathNet.Numerics** library for matrix operations

## 📁 File Structure
- `Program.cs` – Main program logic, encryption/decryption functions, dictionary mapping
- `Cryptography.csproj` – Project configuration file
- `Cryptography.sln` – Visual Studio solution file

## ▶️ How to Run
1. Open the solution `Cryptography.sln` in **Visual Studio**.
2. Restore NuGet packages (MathNet.Numerics).
3. Build the project.
4. Run the console app to see encryption and decryption outputs in the terminal.

Alternatively, using CLI:
```bash
cd Cryptography
dotnet restore
dotnet build
dotnet run
```

## 🔎 Example
```plaintext
Original message: TRYTOBREAKTHISCODE
Encrypted (mod 29): ...
Decrypted (mod 29 → 26): TRYTOBREAKTHISCODE
```

## 📚 Learning Outcomes
- Understanding matrix-based encryption (Hill Cipher)
- Implementing modular arithmetic with special characters
- Using external libraries for mathematical computations
- Structuring clean and maintainable cryptographic code in C#

## 🚀 Future Enhancements
- Add user input for custom messages
- Support 3x3 Hill cipher matrix
- Implement brute-force or frequency-based cracking attempts
- Add GUI for interactive use

## 📄 License
This project is for educational purposes and released under the **MIT License**.

## 👤 Author
Created by Phuc Hoang and Chanphone Visathip – open to feedback, questions, and collaboration!

