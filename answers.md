# CMPS 2200 Assignment 3
## Answers

**Name:**_________________________


Place all written answers from `assignment-03.md` here for easier grading.






- **b.** What are the recurrences for the Work and Span of this solution? What are their Big Oh solutions?

  W(n) = W(n-1) + 1
    
  in O(n)

  S(n) = S(n-1) + 1
  
  in O(n)
  
  
  
- **d.** Assume that any maps are done in parallel, and that we use the efficient implementation of scan from class. What are the recurrences for the Work and Span of this solution?

  W(n) = 2W(n/2) + n
  
  S(n) = S(n/2) + 1





- **f.** Assuming any recursive calls are done in parallel, what are the recurrences for the Work and Span of this solution? What are their Big Oh solutions?

  W(n) = 2W(n/2) + n
  
  in O(n * log n)
  
  S(n) = S(n/2) + 1
  
  in O(log n)
