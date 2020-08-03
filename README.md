# Palindrome Task

### Identifying palindromes
One method is comparing the letters at each end and then move down the word in both directions until you reach the middle. If it's a palindrome, the letters should be the same when compared. For example, '**REDDER**": '*R*' is at both ends, then '*E*' are the next letters, then '*D*'. Having reached the midddle successfully, with each letter being the same each time, you can come to the conclusion that 'REDDER' is a palindrome.\

In Python, you are able to do this by turning a string into a list, then comparing each letter of the list from opposite ends as suggested above, by using indexes.\

