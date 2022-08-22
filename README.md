# Samin_Cellchip
sentence = 'Jim quickly realized that the beautiful gowns are expensive'
count_letters = {}
cnt_lowercase = 0
cnt_uppercase = 0

for c in sentence:
    if (c in count_letters):
        count_letters[c] += 1
    else:
        count_letters[c] = 1

cnt_lowercase = len([i for i in count_letters.keys() if i.islower()])
cnt_uppercase = len([i for i in count_letters.keys() if i.isupper()])

print(count_letters)
print(cnt_lowercase)
print(cnt_uppercase)
