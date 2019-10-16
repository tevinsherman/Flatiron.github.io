---
layout: post
title:      "An interesting problem I solved while learning Data Structure"
date:       2019-10-16 17:30:56 -0400
permalink:  an_interesting_problem_i_solved_while_learning_data_structure
---



An interesting problem I solve while learning data structures was using the *each method *while iterating over a collection of ranges. With the each iterator it returns all the elements of a collection such as range, arrays, or hash.

Ex. range = 1..5

Range.*each do*|numbers| #Your each iterator
puts  “This is the number #{numbers}
end

#Comes Out as:
This is the number 1
This is the number 2
This is the number 3
This is the number 4
This is the number 5

*Each do*|numbers| accesses the each element in the range
****
