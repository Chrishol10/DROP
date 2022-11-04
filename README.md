# DROP
Remove or Drooping specific rows &amp; columns

can anyone help me on the below 2 question on how to code it i have tried multiple ways but getting errors
 1. Analyze the date column and remove the entries if it has an incorrect timeline
 2. Draw scatter and hexbin plots for complaint concentration across Brooklyn
I have tired drop function but im only able to drop the column but not the incorrect entries
2nd one im getting the scatter & hexbin with matplotlib.pyplot library but unable to get the answer specific to above question.

Created Date	Closed Date	City	Borough	Park Borough	Complaint Type	Resolution Action Updated Date
12/31/2015 11:59:45 PM	01-01-16 0:55	NEW YORK	MANHATTAN	MANHATTAN	Noise - Street/Sidewalk	01-01-16 0:55
12/31/2015 11:59:44 PM	01-01-16 1:26	ASTORIA	QUEENS	QUEENS	Blocked Driveway	01-01-16 1:26
12/31/2015 11:59:29 PM	01-01-16 4:51	BRONX	BRONX	BRONX	Blocked Driveway	01-01-16 4:51
12/31/2015 11:57:46 PM	01-01-16 7:43	BRONX	BRONX	BRONX	Illegal Parking	01-01-16 7:43
12/31/2015 11:56:58 PM	01-01-16 3:24	ELMHURST	QUEENS	QUEENS	Illegal Parking	01-01-16 3:24
12/31/2015 11:56:30 PM	01-01-16 1:50	BROOKLYN	BROOKLYN	BROOKLYN	Illegal Parking	01-01-16 1:50
12/31/2015 11:55:32 PM	01-01-16 1:53	NEW YORK	MANHATTAN	MANHATTAN	Illegal Parking	01-01-16 1:53
12/31/2015 11:54:05 PM	01-01-16 1:42	BRONX	BRONX	BRONX	Blocked Driveway	01-01-16 1:42
12/31/2015 11:53:58 PM	01-01-16 8:27	KEW GARDENS	QUEENS	QUEENS	Illegal Parking	01-01-16 8:27
12/31/2015 11:53:58 PM	01-01-16 1:17	BROOKLYN	BROOKLYN	BROOKLYN	Blocked Driveway	01-01-16 1:17
12/31/2015 11:53:58 PM	01-01-16 1:17	JACKSON HEIGHTS	QUEENS	QUEENS	Blocked Driveway	01-01-16 7:41
12/31/2015 11:52:58 PM	01-01-16 7:41	BRONX	BRONX	BRONX	Blocked Driveway	01-01-16 10:58
12/31/2015 11:50:57 PM	01-01-16 10:58	BRONX	BRONX	BRONX	Noise - Street/Sidewalk	01-01-16 2:18
12/31/2015 11:48:03 PM	01-01-16 2:17	BROOKLYN	BROOKLYN	BROOKLYN	Illegal Parking	01-01-16 8:18
12/31/2015 11:47:58 PM	01-01-16 8:18	BROOKLYN	QUEENS	QUEENS	Derelict Vehicle	01-01-16 10:17
12/31/2015 11:47:37 PM	01-01-16 10:17	BROOKLYN	QUEENS	QUEENS	Derelict Vehicle	01-01-16 15:20
12/31/2015 11:47:30 PM	01-01-16 15:20	NEW YORK	QUEENS	QUEENS	Blocked Driveway	01-01-16 4:39
12/31/2015 11:40:55 PM	01-01-16 0:28	BRONX	BROOKLYN	BROOKLYN	Blocked Driveway	01-01-16 0:36
12/31/2015 11:40:43 PM	01-01-16 4:12	MIDDLE VILLAGE	BROOKLYN	BROOKLYN	Noise - Commercial	01-01-16 2:37
12/31/2015 11:38:51 PM	01-01-16 9:11	BROOKLYN	BROOKLYN	MANHATTAN	Noise - Commercial	01-01-16 0:28
12/31/2015 11:34:18 PM	01-01-16 0:50	BROOKLYN	QUEENS	BRONX	Noise - Street/Sidewalk	01-01-16 4:12
![image](https://user-images.githubusercontent.com/116726422/200008873-093086ca-fcc6-447f-80f4-176089fd9b52.png)
