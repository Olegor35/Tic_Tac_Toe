def print_a(a):
    for i in range(len(a)):
        print(a[i], end=" ")
        if (i+1) % 3 == 0:
            print()


a = [0, 1, 2, 3, 4, 5, 6, 7, 8]
print_a(a)
for i in range(len(a)):
    c = input("Кто ходит")
    b = int(input("Номер поля"))
    if b == 0:
        if c == "x":
            a[0] = "x"
            print_a(a)
        elif c == "o":
            a[0] = "o"
            print_a(a)
    if b == 1:
        if c == "x":
            a[1] = "x"
            print_a(a)
        elif c == "o":
            a[1] = "o"
            print_a(a)
    if b == 2:
        if c == "x":
            a[2] = "x"
            print_a(a)
        elif c == "o":
            a[2] = "o"
            print_a(a)
    if b == 3:
        if c == "x":
            a[3] = "x"
            print_a(a)
        elif c == "o":
            a[3] = "o"
            print_a(a)
    if b == 4:
        if c == "x":
            a[4] = "x"
            print_a(a)
        elif c == "o":
            a[4] = "o"
            print_a(a)
    if b == 5:
        if c == "x":
            a[5] = "x"
            print_a(a)
        elif c == "o":
            a[5] = "o"
            print_a(a)
    if b == 6:
        if c == "x":
            a[6] = "x"
            print_a(a)
        elif c == "o":
            a[6] = "o"
            print_a(a)
    if b == 7:
        if c == "x":
            a[7] = "x"
            print_a(a)
        elif c == "o":
            a[7] = "o"
            print_a(a)
    if b == 8:
        if c == "x":
            a[8] = "x"
            print_a(a)
        elif c == "o":
            a[8] = "o"
            print_a(a)
    if a[0] and a[1] and a[2] == "x":
        print("x победил")
        break
    if a[3] and a[4] and a[5] == "x":
        print("x победил")
        break
    if a[6] and a[7] and a[8] == "x":
        print("x победил")
        break
    if a[0] and a[4] and a[8] == "x":
        print("x победил")
        break
    if a[2] and a[4] and a[6] == "x":
        print("x победил")
        break
    if a[0] and a[3] and a[6] == "x":
        print("x победил")
        break
    if a[1] and a[4] and a[7] == "x":
        print("x победил")
        break
    if a[2] and a[5] and a[8] == "x":
        print("x победил")
        break
    if a[0] and a[1] and a[2] == "o":
        print("o победил")
        break
    if a[3] and a[4] and a[5] == "o":
        print("o победил")
        break
    if a[6] and a[7] and a[8] == "o":
        print("o победил")
        break
    if a[0] and a[4] and a[8] == "o":
        print("o победил")
        break
    if a[2] and a[4] and a[6] == "o":
        print("o победил")
        break
    if a[0] and a[3] and a[6] == "o":
        print("o победил")
        break
    if a[1] and a[4] and a[7] == "o":
        print("o победил")
        break
    if a[2] and a[5] and a[8] == "o":
        print("o победил")
        break
