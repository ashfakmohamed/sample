# sample

n = 4

for i in range(1, n + 1):
    for j in range(n - i):
        print(' ', end='')
    for k in range(2 * i - 1):
        print('*', end='')
    print()

def print_pattern(n):
    for i in range(1, n + 1):
        for j in range(n - i):
            print(' ', end='')
        for k in range(2 * i - 1):
            print('*', end='')
        print()

n = 4
print_pattern(n)
