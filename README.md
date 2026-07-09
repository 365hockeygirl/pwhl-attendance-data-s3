# PWHL Attendance Data Season 3

PWHL Season 3 Attendance data generated via HockeyTech/LeagueStat API (lscluster.hockeytech.com)
See PWHL data reference: https://github.com/IsabelleLefebvre97/PWHL-Data-Reference

The Jupyter notebook used to fetch the data is in [/code_to_fetch_data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/tree/main/code_to_fetch_data)

The data generated from the notebook is in [/data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/tree/main/data)
- [average_attendance_by_home_team](https://github.com/365hockeygirl/pwhl-attendance-data-s3/blob/main/data/average_attendance_by_home_team.csv) is the average attendances by home team (regardless of venue, including takeover games). Note that this mostly matches the [official PWHL attendance report](https://lscluster.hockeytech.com/media/pwhl/pwhl/index.php?format=HTML&season_id=8&step=4&sub=15) but my Boston Fleet number is 6560; the official league number is 6,531; I'm not sure where the discrepancy is coming from 😭
- [primary_venue_average_attendance_by_location](https://github.com/365hockeygirl/pwhl-attendance-data-s3/blob/main/data/primary_venue_average_attendance_by_location.csv) is the average attendances by primary home venue
- [primary_venue_attendance_data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/blob/main/data/primary_venue_attendance_data.csv) is a table of all S3 games played at a primary home venue. This table was used to generate `primary_venue_average_attendance_by_location`
- [special_venue_attendance_data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/blob/main/data/primary_venue_average_attendance_by_location.csv) is a table of all games not played at a primary home venue; this includes takeover games and special games like Fleet games at Agganis or the MSG game
- [pwhl_s3_attendance_data](https://github.com/365hockeygirl/pwhl-attendance-data-s3/blob/main/data/pwhl_s3_attendance_data.csv) is a table of all S3 games but note that it's not in chronological order because I appended the non primary venue games and then the primary venue games tables together. I used this to make the `average_attendance_by_home_team` table
