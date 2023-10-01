numbers = [5, 12, 8, 15, 3, 20, 7]

for num in reversed(numbers):
    print(num)
#2
numbers = [5, 12, 8, 15, 3, 20, 7]

user_input = input("Podaj liczbe: ")

try:
    user_number = int(user_input)

    if user_number in numbers:
        print(f"Liczba {user_number} znajduje sie w liscie 'numbers'.")
    else:
        print(f"Liczba {user_number} nie znajduje sie w liscie 'numbers'.")

except ValueError:
    print("To nie jest poprawna liczba.")
#3
numbers = [5, 12, 8, 15, 3, 20, 7]

# liczba ktorej indeks chcemy znalezc
search_number = 3

# sprawdzenie czy liczba istnieje w liscie
if search_number in numbers:
    index = numbers.index(search_number)
    print(f"Indeks pierwszego wystapienia liczby {search_number} w liscie 'numbers' to: {index}")
else:
    print(f"Liczba {search_number} nie wystepuje w liscie 'numbers'.")
