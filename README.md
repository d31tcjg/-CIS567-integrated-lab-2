# -CIS567-integrated-lab-2

# Take input
input_string = input()

# Split input into character and phrase
char_to_count = input_string[0]
phrase = input_string[2:]  # Skip the first character and space

# Count occurrences of the character
count = phrase.count(char_to_count)

# Determine the correct output format
if count == 1:
    print(f'{count} {char_to_count}')
else:
    print(f'{count} {char_to_count}\'s')
