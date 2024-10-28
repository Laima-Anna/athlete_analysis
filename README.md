# Data Analysis of Ultra-marathon Runners

## Problem Definition


## Dataset
Dataset was taken from kaggle.com ([Available here](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running))

Dataset consists of:
- 7,461,226 ultra-marathon race records from 1,641,168 unique athletes
- Columns:
    - Year of event
    - Event dates (object)
    - Event name (object)
    - Event distance/length (object)
    - Event number of finishers (int64)
    - Athlete performance (object)
    - Athlete club (object)
    - Athlete country (object)
    - Athlete year of birth (float64)
    - Athlete gender (object)
    - Athlete age category (object)
    - Athlete average speed (object)
    - Athlete ID (int64)

## Strategies for data anaysis

- Data cleaning:
    - Extracting event country codes
    - Parsing event dates
    - Converting distances to the same format
    - Extracting distance and performance
    - Converting perfromance to the same format
    - Calculating average speed in km/h
    - Removing Null elements
    - Checking for outliers and filling if required
    - Categorizing event distances
- Analysis: 
    - Distribution plots for average speed, race distances, age
    - Gender analysis in general, per event, per distgance category
    - Minimum and maximum age per distance category
    - Speed vs age 
    - Most common events
    - Specific event analysis of gender, speed, age and top athletes
    - Particular athlete analysis on number of events, and speed analysis over time


## Results

General:
- Country with most ultra-marathon events hosted is USA


Latvia events:
- Average speed follows normal distribution
- There are more males participating than females
- There are more runners finishing the ultra-marathons starting 2005 in Latvia
- Runners participating in Latvian events are mainly from Latvia
- All events except for Taliharja Vanakuri Winter Ultra Endurance Race have more males than females paricipating
- The most popular event is Skrejiens Riga-Valmiera
- Most common event category is 90km to 120km
- Athlete age and average speed follow normal distribution
- Youngest participant of age eleven participated in the 40km to 70km category
- Eldest participant of age 76 participated in the 40km to 70km category
- Fastest runners are in category M23 (men 23 years old)
- Slowest runners are in category WU23 (women under 23 years old)


Event Skrejiens Riga-Valmiera:
- The event was hosted in years 1989-1993 and 2014-2022
- Age is a major factor where younger and elder participants choose a slower pace
- The top althletes got faster (1989: 10:07 hours, 2022: 8:25 hours)
- Two athletes with IDs 129264 and 66095 got into top 3 three times each
- Number of athletes who participated more than once are 224 out of 589

Athlete (111276) from Latvia with most competitions:
- Participated in events starting 1984, ending in 2019 (76 years old)
- In 1993, he participated in the highest number of events which is 14
- The athlete participated mostrly in events hosted in USA and Latvia
- The athlete mostly participated in events with distances 90km to 120km, although he has a substancial number of events over 800km
- The athlete's average speed decresed as the years went on