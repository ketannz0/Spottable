# Spottable
Approaches taken to answer the questions are as follows:
I have used Python for analysing the data and displaying the desired result. Starting with uploading the Json file in python and displaying the data in an organised manner to carefully observe and look into the data.Library used : Json, Datetime and Timezone.


•	For finding the Total Experience of each candidate, I have calculated the sum of number of days between the start date and end date of joining in each Company and at the end, I converted the sum (which is in days) into years and thus I got the Total experience of each candidate

•	For finding Most and Least Amount of Time that the candidate had spent in an organisation, I have calculated the number of days that the candidate had spent in a particular Company, and I have put the days in a list and later I have founded the least and the most number of days spent from that list and displayed the desired name of the company.

•	For finding the Gap in the career of a candidate, I have taken the joining and leaving year in a list and compared the last leaving year of the company with the next joining year of another company, if they are not same then it means that the person is having a gap in his career. (I have referred gap as in year that is minimum 1 year)

Problems Faced:
Data was given in the form of list of Dictionaries which makes it difficult to work in the data, so I have converted the Json data in Dictionary of list, so that I can work in the data using desired key values which is more comfortable for me.
Data was Irregular as some columns had null value, for example : in some cases end date was not there, then I have set the end date as present date.
Format of dates in the data was different in some cases which makes the calculations difficult, so I have taken different possible formats of date and compared with the give data and performed the calculations.
