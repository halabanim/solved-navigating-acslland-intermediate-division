Download Link: https://assignmentchef.com/product/solved-navigating-acslland-intermediate-division
<br>
PROBLEM:  In taking a vacation trip, MapQuest and Google Maps provide very valuable information.  Newer versions of these on-line tools provide not only the distance traveled, but also how long it will take you and how much it will cost for gasoline.  In this program, you will be traveling a sequential route through ACSLland with all destinations given in alphabetical order.  Each time that you input two cities, the kind of vehicle you are driving, the kind of highway it is, and the cost per gallon of gasoline, print out the total distance between these two inputted cities, the total time it should take you, and the total cost of gasoline.  Assume that the following information between each pair of adjacent cities on your route is given below:




A to B – 450 miles                  B to C – 140 miles                  C to D – 120 miles

D to E – 320 miles                  E to F – 250 miles                  F to G – 80 miles




For example, if you are driving a mid-size vehicle and driving on the highway from city A to city C with a cost of $3.79/gallon, output 590 miles, “09:50” hours and minutes, and $89.44 for gas.




Given the following kinds of cars and types of roads,

Compact(C):  28 m/gal                                                           Interstate(I):       65 miles/hour

Mid-size(M): 25 m/gal                                                             Highway(H):    60 miles/hour

Full-size(F):    22 m/gal                                                          Main roads(M):  55 miles/hour

Van/SUV(V): 20 m/gal                                                            Side roads(S):    45 miles/hour




INPUT:  There will be 5 lines of input.  Each line will contain four letters for the starting city, the ending city, the kind of vehicle, and the type of road followed by the average cost for a gallon of gasoline.




OUTPUT:  For each input line, print the total distance traveled, the total hours and minutes in “hh:mm” format with two 2-digit whole numbers and a colon between them, and the total cost for gas in “$xxx.xx” format with a dollar sign and exactly two decimal places.







SAMPLE INPUT                                                                    SAMPLE OUTPUT




<ol>

 <li>A, C, M, H, 3.79                                                               590, 09:50, $89.44</li>

 <li>E, F, C, S, 3.69                                                               250, 05:33, $32.95 3.  B, E, F, M, 3.59                                                                     3.  580, 10:33, $94.65</li>

 <li>F, G, V, H, 3.89                                                               80, 01:20, $15.56</li>

 <li>A, G, C, I, 3.63                                                               1360, 20:55, $176.31</li>

</ol>


