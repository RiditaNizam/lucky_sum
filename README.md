# lucky_sum
CodingBat Python Logic-2

Given 3 int values, a b c, return their sum. However, if one of the values is 13 then it does not count towards the sum and values to its right do not count. So for example, if b is 13, then both b and c do not count.

def lucky_sum(a, b, c):

    sum = 0
    if a == 13:
      sum == 0
    elif b == 13:
      sum += a
    elif c == 13:
      sum += (a + b)
    elif a != 13 and b != 13 and c != 13:
      sum += a + b + c
    return sum
