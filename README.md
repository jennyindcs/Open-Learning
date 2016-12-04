# Open-Learning
A distance learning course data set which contains information about students' online learning


## Description
This data set contains demographic information of students who registered for a distance learning course provided by the Open University (UK), student interactions with the virtual learning environment for the course, and final results of students.

All information contained in this data set is anonymised. The data set is obtained from the Open University Learning Analytics dataset [1].


## Encoding
The following encoding mapping is used to convert the original data to a format that is more appropriate for advanced data analytics techniques such as clustering algorithms.

#### gender

1 = M
2 = F

#### region

1 = East Anglian Region
2 = East Midlands Region
3 = Ireland
4 = London Region
5 = North Region
6 = North Western Region
7 = Scotland
8 = South East Region
9 = South Region
10 = South West Region
11 = Wales
12 = West Midlands Region
13 = Yorkshire Region

#### highest_education

1 = Lower Than A Level
2 = A Level or Equivalent
3 = HE Qualification
4 = Post Graduate Qualification

#### imd_band

start from 1, increasing by 1 from 0-10% to 90-100%
missing value = 0

#### age_band

1 = 0-35
2 = 35-55
3 = 55<=

#### disability

1 = Y
2 = N

#### final_result

1 = Distinction
2 = Pass
3 = Fail
4 = Withdrawn


## License
This data set is released under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.


## Reference

[1] Kuzilek, J., Hlosta, M., Herrmannova, D., Zdrahal, Z. and Wolff, A. OU Analyse: Analysing At-Risk Students at The Open University. Learning Analytics Review, no. LAK15-1, March 2015, ISSN: 2057-7494.

