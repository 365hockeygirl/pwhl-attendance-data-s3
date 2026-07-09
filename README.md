# PWHL Attendance Data Season 3

✨ SUBSCRIBE TO [365 HOCKEY GIRL NEWSLETTER](https://365hockeygirl.beehiiv.com/subscribe) TO READ THE WRITE UP! ✨

## Graphs 📊
Graphs can be found in [/graphs](https://github.com/365hockeygirl/pwhl-attendance-data-s3/tree/main/graphs)

<img width="700"  alt="pwhl average attendance vs capacity" src="https://github.com/user-attachments/assets/0111e7cb-97aa-4bbc-82d7-bed283bcd332" />
<img width="700" alt="tsongas center attendance" src="https://github.com/user-attachments/assets/b472a58f-7181-4aac-bcf2-a1c7008dc2cc" />
<img width="700" alt="CPA attendance" src="https://github.com/user-attachments/assets/02b5e30b-b1dd-45b9-8cb9-2717131a1512" />
<img width="700" alt="Prudential Center Attendance" src="https://github.com/user-attachments/assets/32118fad-ee59-4552-95cc-8b86d23995de" />

## Dataset Generation 💻
PWHL Season 3 Attendance data generated via HockeyTech/LeagueStat API (lscluster.hockeytech.com)
See PWHL data reference: https://github.com/IsabelleLefebvre97/PWHL-Data-Reference

The Jupyter notebook used to fetch the data is in [/code_to_fetch_data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/tree/main/code_to_fetch_data) 

## Dataset
The data generated from the notebook is in [/data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/tree/main/data)
- 📁 S3 Regular season attendance: lists attendances for every regular season game. Also contains separate datasets for just primary venues vs "special" venues (takeover games, one-off games)
- 📁 S3 regular season average attendances: Average attendances based on home team or primary venue
- 📁 S3 Playoffs attendances: lists attendances for playoffs, also gives a combined dataset for all games including regular season and playoffs
- 📁 arena characteristics: arena capacities
