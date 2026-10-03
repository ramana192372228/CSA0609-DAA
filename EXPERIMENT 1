AIM
To design and implement an algorithm to find the first palindromic string in an array of strings and analyze its time and space complexity.
ALGORITHM
1. Start.
2. Given an array of strings words.
3. Traverse each string from left to right.
4. For each string, set two pointers:
   - left = 0
   - right = length - 1
5. Compare the characters at left and right.
6. If they are different, the string is not a palindrome.
7. If they are the same, move left forward and right backward.
8. If the complete string is a palindrome, return it immediately.
9. If no palindrome is found, return an empty string.
10. Stop.
PSEUDOCODE
Algorithm FirstPalindrome(words)

    for each word in words do
        left ← 0
        right ← length(word) - 1
        isPalindrome ← TRUE

        while left < right do
            if word[left] ≠ word[right] then
                isPalindrome ← FALSE
                break
            end if

            left ← left + 1
            right ← right - 1
        end while

        if isPalindrome = TRUE then
            return word
        end if
    end for

    return ""
End Algorithm

PYTHON PROGRAM
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
OUTPUT
First Palindromic String: ada

COMPLEXITY ANALYSIS
Let:
- n = number of strings
- m = maximum length of a string
Time Complexity: O(n × m)
In the worst case, every string may need to be checked, and each string can require up to m/2 character comparisons.
Space Complexity: O(1)
Only a few variables (left, right, and is_palindrome) are used, so no additional data structure is required.
RESULT
Thus, the algorithm was successfully designed and implemented in Python to find the first palindromic string in an array, and its time complexity was found to be O(n × m) with O(1) auxiliary space.
