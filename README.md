# 3 ta sondan eng kattasini topuvchi dastur

def eng_kattasini_top(a, b, c):
    if a >= b and a >= c:
        return a
    elif b >= a and b >= c:
        return b
    else:
        return c

a = float(input(" "))
b = float(input("2-sonni kiritin1-sonni kiriting:g: "))
c = float(input("3-sonni kiriting: "))

# Natijani hisoblash
katta_son = eng_kattasini_top(a, b, c)

print(f"\nKiritilgan sonlar orasida eng kattasi: {katta_son}")
