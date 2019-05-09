# Siege
​
## What is it?
-----------
Siege is an open source regression test and benchmark utility.
It can stress test a single URL with a user defined number of
simulated users, or it can read many URLs into memory and
stress them simultaneously. The program reports the total
number of hits recorded, bytes transferred, response time,
concurrency, and return status. Siege supports HTTP/1.0 and 1.1
protocols, the GET and POST directives, cookies, transaction
logging, and basic authentication. Its features are configurable
on a per user basis.
​
Most features are configurable with command line options which
also include default values to minimize the complexity of the
program's invocation. Siege allows you to stress a web server
with `n` number of users `t` number of times, where `n` and `t` are
defined by the user. It records the duration time of the test
as well as the duration of each single transaction. It reports
the number of transactions, elapsed time, bytes transferred,
response time, transaction rate, concurrency and the number of
times the server responded OK, that is status code 200.
​
Siege was designed and implemented by Jeffrey Fulmer in his
position as Webmaster for Armstrong World Industries. It was
modeled in part after Lincoln Stein's torture.pl and its data
reporting is almost identical. But torture.pl does not allow
one to stress many URLs simultaneously; out of that need siege
was born....
​
When an HTTP server is being hit by the program, it is said to be
"under siege."
​
​
## Why do i need it?
-----------------
Siege was written for both web developers and web systems
administrators. It allows those individuals to test their programs
and their systems under duress. As a web professional, you are
responsible for the integrity of your product, yet you have no
control over who accesses it. Traffic spikes can occur at any
moment. How do you know if you're prepared?
​
Siege will allow you to place those programs under duress, to
allow you to better understand the load that they can withstand.
You'll sleep  better knowing your site can withstand the
weight of 400 simultaneous transactions if your site currently
peaks at 250.
