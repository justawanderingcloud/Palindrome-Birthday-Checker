# My girlfriend and I are almost 9 years apart.
# She turned 23 this year, I am going to turn 32.
# I wondered how many of there "palindrome" birthdays we were going to have.
# Sure you could calculate that on your fingers.
# Or do a quick spreadsheet.
# That is not why we code though.

gf1 = [str(item) for item in range(1, 90)]
bf1 = [str(item) for item in range(10, 99)]
bf2 = [item[::-1] for item in bf1]

gfbf = dict(zip(gf1, bf2))

birthdays = {k: v for (k, v) in gfbf.items() if k == v}

gf2 = birthdays.keys()
bf3 = birthdays.values()
bf4 = [item[::-1] for item in bf3]

birthdaysfinal = dict(zip(gf2, bf4))

print(birthdaysfinal)
