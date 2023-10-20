simple


inclass(john, cmsc330). inclass(mary, cmsc330). inclass(george, cmsc330). inclass(jennifer, cmsc330). inclass(john, cmsc311). inclass(george, cmsc420). inclass(susan, cmsc420).

?-inclass(john, cmsc330).  “yes”
?- inclass(susan, cmsc420).  “yes”
?- inclass(susan, cmsc330).  “no”


speed(ford,100). speed(chevy,105). speed(dodge,95).
speed(volvo,80).
time(ford,20).
time(chevy,21).
time(dodge,24).
time(volvo,24).
distance(X,Y) :- speed(X,Speed),
                    time(X,Time),
                    Y is Speed * Time.


