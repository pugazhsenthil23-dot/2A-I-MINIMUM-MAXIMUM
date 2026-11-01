# 2A-I-MINIMUM-MAXIMUM# Experiment 2(a)(i): Find Minimum and Maximum of Two Numbers Using PROLOG

## Aim

To implement decision making and knowledge representation using the PROLOG tool.

## Procedure

The manual does not provide a separate step-by-step procedure for this program. The following steps describe how to execute the given PROLOG rules.

1. Open a PROLOG interpreter.
2. Define rules to find the minimum of two numbers.
3. Define rules to find the maximum of two numbers.
4. Load the PROLOG program.
5. Execute queries to find the minimum and maximum values.
6. Display the results.

## Prolog Code

```prolog
% Rule to find the minimum of two numbers
minimum(X, Y, X) :- X =< Y.
minimum(X, Y, Y) :- X > Y.

% Rule to find the maximum of two numbers
maximum(X, Y, X) :- X >= Y.
maximum(X, Y, Y) :- X < Y.
```

## Example Queries and Outputs

### Query 1: Find the Minimum

```prolog
?- minimum(5, 10, Min).
```

**Output:**

```text
Min = 5.
```

### Query 2: Find the Maximum

```prolog
?- maximum(5, 10, Max).
```

**Output:**

```text
Max = 10.
```

### Query 3: Find Both Minimum and Maximum

```prolog
?- minimum(8, 3, Min), maximum(8, 3, Max).
```

**Output:**

```text
Min = 3,
Max = 8.
```

## Result

Thus, the PROLOG program to find the minimum and maximum of two numbers was implemented successfully.

```

**Progress: 5 / 11**

| Experiment | Topic | Status |
|---|---|---|
| 1(a) | Eight Queens | ✅ |
| 1(b) | Depth First Search | ✅ |
| 1(c) | MINIMAX | ✅ |
| 1(d) | A* Search | ✅ |
| 2(a)(i) | Minimum and Maximum | ✅ |
| 2(a)(ii) | Simple Clauses | ⏳ |

Type **NEXT** for Simple Clauses, macha!
```
