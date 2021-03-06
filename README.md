# WalnutCreekTDM
This script takes in Streetlight O-D data, summarize the number of OD trips by Day Type, Time of Day, and Trip Purpose. It outputs heatmaps of OD zones for trips to and from Walnut Creek.

Python 2.7 with Pandas 0.23.4

Input data: 'OD_TP.csv'

1) Day Type: '0: Average Day (M-Su)', '1: Average Weekday (Tu-Th)', '2: Average Weekend Day (Sa-Sa)'

2) Day Part: '00: All Day (12am-12am)', AM Peak - '08: 7am (7am-8am)', '09: 8am (8am-9am)', PM-Peak - '17: 4pm (4pm-5pm)', '18: 5pm (5pm-6pm)'

Output: Heatmap plots by OD, Day Type, ToD, and Trip Purpose

---

This script takes in Streetlight O-M-D data, summarize the number of OMD trips by Day Type, Time of Day, and Middle Filter.
It outputs heatmaps of OD zones for trips to and from Walnut Creek.

Python 2.7 with Pandas 0.23.4

Input data: 'OMD.csv'


1) Day Type: '0: Average Day (M-Su)', '1: Average Weekday (Tu-Th)', '2: Average Weekend Day (Sa-Sa)'

2) Day Part: '00: All Day (12am-12am)', AM Peak - '08: 7am (7am-8am)', '09: 8am (8am-9am)', PM-Peak - '17: 4pm (4pm-5pm)', '18: 5pm (5pm-6pm)'

3) Middle Filters: 'N Main S of Sunnyvale', 'Treat Blvd @ Walnut Creek', 'Lawrence Way I-680 On Ramp', 'Ygnacio Valley E of I-680', 'California Blvd S of Ygnacio Valley Rd', 'N Main St S of Ygnacio Valley Rd', 'Mt Diablo Blvd E of I-680', 'Olympic Blvd E of I-680', 'Ygnacio Valley @ Walnut Creek Eastern Boundary', 'Treat @ Lime Ridge', 'Civic Dr S of Ygnacio Valley Rd', 'Ygnacio Valley btw Homestead & Montego'

Output: Heatmap plots by OD, Day Type, ToD, and Middle Filter
