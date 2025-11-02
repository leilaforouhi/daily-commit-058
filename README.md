def fibonacci(n):
    sequence = [0, 1]
    while len(sequence) < :
        sequence.append(sequence[-1] + sequence[-2])
    return sequence[:n]

if __name__ == "__main__":
    count = 10
    print(f"Fibonacci sequence ({count} terms): {fibonacci(count)}")
