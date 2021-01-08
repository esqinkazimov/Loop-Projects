The program implements Newton’s method to compute and display the square
root of a number entered by the user. The algorithm for Newton’s method follows:

Read x from the user
Initialize guess to x/2
While guess is not good enough do
Update guess to be the average of guess and x/guess

When this algorithm completes, guess contains an approximation of the square
root. The quality of the approximation depends on how you define “good enough”.
In the my solution, guess was considered good enough when the absolute value
of the difference between guess^2 and x was less than or equal to 10^-14
