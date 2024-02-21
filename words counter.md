def count_words(sentence):
    # Split the sentence into words based on whitespace
    words = sentence.split()
    # Return the number of words
    return len(words)

# Example usage:

sentence =input("Enter the sentence ")
word_count = count_words(sentence)
print(f"The sentence contains {word_count} words.")
if (word_count==0):
    print("Please enter the sentence")
