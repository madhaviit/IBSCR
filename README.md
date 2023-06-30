# IBSCR
InterviewBit Leaderboard Scraping

# Contributor
- [Madhav Kadam](https://github.com/madhaviit)

# Features
- One can fetch cuurent InterviewBit Rankings of all the users along with their statistics into single csv file.
- Disclaimer : This notebook I have created for myself to just learn WebScraping.

# Guide
- open the SimpleIbscraper.ipynb and install the required libraries.
- Change the starting and ending ranks that you would like to fetch in the designated area.
- Login to Interviewbit with your credentials and open the network section of developer tools of the browser.
- Now, go to leaderboard. There will be multiple network requests. Among all of them, choose the first one that is being made to "interviewbit.com" and copy its bash cURL and convert it to python commands using any of the curl to python converter. (I used [curlconverter](https://curlconverter.com/).)
- Paste it to designated area.
- Now run this code section. It usually takes 30 min per 20000 records.
- Run further sections to create a .csv file out of fetched records.
- If you are usign google colab, run the download section.
