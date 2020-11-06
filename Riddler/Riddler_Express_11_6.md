## First run
The first 20 mile run takes 180 minutes at a pace of 9 minutes per mile, or 1/9 miles per minute. 

## Second run
The second run has a varying pace and acceleration. If we model the pace as a measure of minutes per mile, then the pace is the inverse of the velocity, as velocity generally measures distance per time traveled, which in this case is miles per minute.

Let t = current time into run, T = total time of run, v = velocity, and d = distance traveled as a function of time t.

Then 1/v = 10 - 2t/T, measured in minutes per mile.
It follows that v = 1/(10 - 2t/T).

We know that the total distance traveled is the integral of the velocity with respect to time, evaluated from 0 to T.
Taking the integral of 1/(10-2t/T) with respect to t and evaluating it at T and 0 while doing some simplification, we get d = -1/2 * T * (log(10 - 2) - log(10)).

Substituting in d = 20 and simplifying, we get that T = 20 * 2 / (log(8) - log(10)). Evaluating the expression, we get ~179.256 minutes, or 40/(log(10) - log(8)) minutes. Can also be viewed as 2:59:15.41.

## Final solution
The second run is faster by about 45 seconds, as the first run takes 180 minutes and the second one takes 179.256 minutes.
