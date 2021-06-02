# Pizzabox

## Project Description

Not impressed with UberEats, DoorDash, GrubHub pizza offerings?
You can now try PizzaBox, the latest food delivery service. 
It is a web application focused on nothing but pizzas.

## Technologies Used

+ .NET Core - C#
+ .NET Core - EF + SQL
+ .NET Core - xUnit
+ ASP.NET Core - MVC

## Features
+ Select a Store
+ Select a Pre-Made Pizza
+ Customize your own Pizza with custom toppings
+ Checkout page with Order

## Getting Started
+ 'git clone https://github.com/rossclark-24/pizzabox-web.git'
+ Install Entity Framework Design
- 'dotnet add package Microsoft.EntityFrameworkCore.Design'
+ Install Entity Framework Core
- 'dotnet add package Microsoft.EntityFrameworkCore'

## Usage
+ Run locally or deploy using any method necessary
+ From main folder run : 'dotnet run -p PizzaBox.Client' to run locally

## Architecture

- [solution] PizzaBox.sln
  - [project - mvc] PizzaBox.Client.csproj
    - [directory] Singletons
  - [project - classlib] PizzaBox.Domain.csproj
    - [directory] Abstracts
    - [directory] Models
  - [project - classlib ] PizzaBox.Storing.csproj
    - [directory] Repositories
  - [project - xunit] PizzaBox.Testing.csproj
    - [directory] Tests

## Requirements

The application is centered around the interaction of 4 main objects:
- Customer
- Order
- Pizza
- Store

## Contributors
+ Ross Clark

## License
MIT License

Copyright (c) 2021 Ross Clark

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

