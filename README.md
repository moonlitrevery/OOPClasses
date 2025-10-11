# Python OOP Class Exercises

This repository contains a collection of three independent exercises designed to demonstrate fundamental concepts of **Object-Oriented Programming (OOP)** in Python. Each exercise is accompanied by comprehensive unit tests using `pytest`.

## Exercises Overview

This collection covers the following key OOP concepts:

| Exercise | Main OOP Concept | Description |
| :--- | :--- | :--- |
| **Library System** | **Inheritance** (`Midia` base class) | Models books and movies, demonstrating class inheritance and dynamic properties (`@property`) to calculate media age. |
| **Banking Account** | **Basic Class Design & Encapsulation** | A simple class to manage a bank account, including deposit, withdrawal, and statement generation with error handling. |
| **Shopping Cart** | **Composition** (`Carrinho` composed of `Item`s) | Models an e-commerce shopping cart, showing how one class is composed of instances of another, and calculates the total value. |

## Files in this Repository

| File Name | Exercise | Concepts Demonstrated |
| :--- | :--- | :--- |
| `Biblioteca.py` | Library System | Inheritance (`Midia`, `Filme`, `Livro`), `@property` |
| `Conta.py` | Banking Account | Class Design, Methods, Error Handling |
| `Carrinho.py` | Shopping Cart | Composition (`Item` inside `Carrinho`), Logic |
| `test_conta.py` | Banking Account Tests | Unit testing deposits, withdrawals, and exceptions (pytest) |
| `test_carrinho.py` | Shopping Cart Tests | Unit testing item management, subtotal, and total calculation (pytest) |

## How to Run

### Prerequisites

⚠️ Ensure you have the `pytest` library installed to run the unit tests

Running the Tests
To execute all unit tests across the exercises:
``pytest``

Running the Programs Interactively
Each main file can be run independently to interact with its console menu:
```bash
python Biblioteca.py
python Conta.py
python Carrinho.py
