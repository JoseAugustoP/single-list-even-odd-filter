list = [[],[]]
n = 0
for c in range(1,8):
    n = int(input(f'Enter a {c}o value: '))
    if n % 2 == 0:
        list[0].append(n)
    else:
        list[1].append(n)
print(f'The even values ​​entered were: {list[0]}')
print(f'The odd values entered were: {list[1]}')
