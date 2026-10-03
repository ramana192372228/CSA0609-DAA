def first_palindrome(words):
    for word in words:
        left = 0
        right = len(word) - 1
        is_palindrome = True

        while left < right:
            if word[left] != word[right]:
                is_palindrome = False
                break

            left += 1
            right -= 1

        if is_palindrome:
            return word

    return ""


# Input
words = ["abc", "car", "ada", "racecar", "cool"]

# Find first palindrome
result = first_palindrome(words)

# Output
print("First Palindromic String:", result)
