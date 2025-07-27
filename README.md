
# MOOC.fi Part4 Exercise 37 - Esmerlyn Garabito Solution

Given a list of integers, let's decide that two consecutive items in the list are neighbours if their difference is 1. So, items 1 and 2 would be neighbours, and so would items 56 and 55.

Please write a function named longest_series_of_neighbours, which looks for the longest series of neighbours within the list, and returns its length.

For example, in the list [1, 2, 5, 4, 3, 4] the longest list of neighbours would be [5, 4, 3, 4], with a length of 4.

An example function call:

my_list = [1, 2, 5, 7, 6, 5, 6, 3, 4, 1, 0]
print(longest_series_of_neighbours(my_list))

__________________________________________________________________

# Areas of Improvement

I realized my solution is more complex than it needs to be. Specifically:

I added an extra number to the list to force the loop to check the last sequence, but I now know this can be handled in a cleaner way.

My approach could be simplified by avoiding extra list
manipulation and using a direct difference check (or the abs() function, which I learned about after completing this solution).

In the future, I want to focus on writing simpler, cleaner code.
