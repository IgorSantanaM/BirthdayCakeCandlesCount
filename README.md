# Birthday Cake Candles

This project contains a C# solution to the "Birthday Cake Candles" problem. The problem involves counting how many candles are tallest on a cake.

## Problem Description

You are given a list of candle heights, where each integer represents the height of a candle on a cake. Your task is to find out how many candles are tallest. For example, if the tallest candles have a height of `h`, you need to count all the candles having height `h`.

### Example

Given candles heights: `[3, 2, 1, 3]`

- The tallest candles have a height of `3`.
- There are `2` candles with height `3`.

Therefore, the output should be `2`.

## Implementation Details

The solution involves a function `birthdayCakeCandles` that takes a list of integers representing candle heights as input and returns an integer representing the count of tallest candles.

### Function Signature

```csharp
public static int birthdayCakeCandles(List<int> candles)
```
### Input Format
The first line of input contains an integer n, which indicates the number of candles.
The second line contains n space-separated integers, each representing the height of a candle.
### Output Format
Output a single integer, the number of tallest candles.
How to Use
Prerequisites
.NET SDK installed on your machine.
Clone the Repository
Clone this repository to your local machine using:
``` bash
git clone https://github.com/IgorSantanaM/BirthdayCakeCandles.git
```
Navigate to the Project Directory
``` bash
cd BirthdayCakeCandles
```
Run the Application
To run the application, use the following commands:
``` bash
dotnet restore
dotnet run
```
This will compile the application, restore any necessary packages, and execute the Main method in Solution.cs, which reads input from the console, calculates the number of tallest candles using the birthdayCakeCandles function, and prints the result.
