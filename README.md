import itertools

digits = '0123456789'
code_length = 8

combinations = [''.join(p) for p in itertools.product(digits, repeat=code_length)]

for combination in combinations:
    print(combination)
👀 I’m inter
