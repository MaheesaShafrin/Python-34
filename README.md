# Python-34
Write a Python program that accepts a comma separated sequence of words as input and prints the unique words in sorted form (alphanumerically).
 items = input("Input comma separated sequence of words: ")

words = [word.strip() for word in items.split(",")]

print(",".join(sorted(set(words))))

Output:

Input comma separated sequence of words: apple, mango, banana
apple,banana,mango

