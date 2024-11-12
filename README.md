# -CIS567-integrated-lab-2

input_string = input()

char_to_count = input_string[0]
phrase = input_string[2:]  # Skip the first character and space

count = phrase.count(char_to_count)

if count == 1:
    print(f'{count} {char_to_count}')
else:
    print(f'{count} {char_to_count}\'s')
