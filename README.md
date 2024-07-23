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
