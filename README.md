# DataAnalyticsProject

## Download the Dataset at:
https://www.kaggle.com/cityofLA/los-angeles-traffic-collision-data

## Data cleaning to-do list: 
(Add items that need to be addressed in order to clean the data. If you've also handled the cleaning, upload/update cleaning code, and comment what you've done.) 
- Victim Sex (what is H and N? Set those to X) (Hannah)
- MO Codes (Many missing)
- LA Specific PLans (we don't know what it is?)

**** To discuss at next meeting: I think we need to create a column of unique incidents in order to use pivot/groupby. DL Number is not unique. I would suggest using a combo of DL Number and Date or DL Number and Location. ****

## Questions to Answer 
- Time Series 
    - Average number of accidents per hour plotted as time series (x= hour of the day, y= avg numb accidents) (Hannah)
    - Do the timings of accidents vary depending on day of the week? (Pooja)
- Demonstrate skills with GroupBy and/or Pivot Table (Hannah - groupby)
- Reporting date same as incident date? Check to make sure. YES THEY ARE ALL THE SAME!!! (Hannah)
- District which reported the most? (Hannah)
- Is there a relationship between time and location? (Hannah)
- More accidents in particular areas, given particular time? (similar to one above; Hannah)
- Which location has most accidents? (Rachel)
- At what time do most accidents occur? (Hannah)
- Zipcode frequency of accident? (Rachel)
- Victim age and time relationship? (Pooja)
- Area name (Khyathi)
Collisions by Area name (Khyathi)
- Collisions per year (Khyathi)
- Collisions per month (Khyathi)
- Collsioons per weekday (Khyathi)
- Who gets in a crash in a parking lot? (Pooja)
- Victim demographics - who gets into crashes? (Hannah - I got average age of accidents grouped by sex then descent)
- Which council districts appear most often? (Rachel)

---
## Project Timeline: 
- July 31: Choose dataset, clean data, explore dataset with basic visualization, reshaping, etc. 
- Aug 1: Complete any additional cleaning, continue exploratory analysis. 
- Aug 2: Work on visualizations for basic business questions. 
- Aug 3 & 4: Visualizations and begin clustering modeling. 
- Aug 5: Continue clustering model & visualizations for basic business questions. 
- Aug 6: Finalize clustering model
- Aug 7: Compile final Jupyter notebook (DEADLINE: ALL WORK IN PYTHON SHOULD BE SUBSTANTIALLY FINISHED) 
- Agu 8: Finalize the Jupyter notebook we will submit. No changes after this date. Begin exec. summary & slide deck. 
- Aug 9: Continue work on write-up and slide deck. (R Exam is due, so we may have limited time to work on this project.)
- Aug 10 & 11: Finalize and submit executive summary, slide deck, and Jupyter notebook. Prepare presentation. Practice presentation. 
- Aug 12: Project due - we will present on either 12 or 13. 
