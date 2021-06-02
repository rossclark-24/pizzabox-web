# Pizzabox

## Project Description

Not impressed with UberEats, DoorDash, GrubHub pizza offerings?
You can now try PizzaBox, the latest food delivery service. 
It is a command line-based application focused on nothing but pizzas.

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
+'git clone 

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

