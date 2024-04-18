### `/scripts`

Contains executable scripts useful for tasks like setting up environments, running tests, and deployment. Currently, the Python code in this directory is for parsing the data files collected by the system.  

There are three types of files that can be parsed:

1)  Flight files from the onboard SD card.  This is very dense data that can be displayed in Excel or another spreadsheet.  However, these take
    a lot of time to setup and each is unique.  The code here will output many plots of the flight data for subsequent analysis.

2)  Telemetry files from the ground station.  These files are relatively small, but the code will graphically display all the important data streams.

3)  Bench Test files from the flight computer.  Bench tests run the system through its paces, testing all features enabled in the settings file.
    I highly recommend examining the data from the bench tests before an actual flight takes place.  This will identify any potential problems.
