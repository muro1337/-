# -
s = input()
h = len(s) // 2
print(s[:h] == s[:len(s)-h-1:-1])

Берём строку и при помощи срезов проверяем, равна ли её первая половина второй, записанной в обратном порядке. Если в строке нечётное количество символов, то средний символ не участвует в проверке, т.к. не влияет на результат.
