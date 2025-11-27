# coffee-concentration-analyzing
README – Challenge 1 (Team A)

1. Project Structure
--------------------
Place the project like this:

challenge1_teamA/
    data/
        raw/
        cleaned/
            final/
    src/
        1.Caffeine_log.ipynb
        2.Sleep_score.ipynb
        3.HRV_Clean.ipynb
        4.Clean_test1.ipynb
        5.Clean_test2.ipynb
        6.Clean_survey.ipynb
        7.Final_analysis.ipynb

2. How to Run (Order)
---------------------
Run notebooks in this order:
1. 1.Caffeine_log.ipynb
2. 2.Sleep_score.ipynb
3. 3.HRV_Clean.ipynb
4. 4.Clean_test1.ipynb
5. 5.Clean_test2.ipynb
6. 6.Clean_survey.ipynb
7. 7.Final_analysis.ipynb

3. Notes
--------
- All notebooks use dynamic paths based on the project folder.
- HRV_Clean renames raw HRV files (adds _cleaned). They won’t be processed again unless the suffix is removed.
- final_data.csv will appear in data/cleaned/final/.

4. Final Output
----------------
final_data.csv contains:
Datetime, Date, Dose_mg, Readiness, SleepScore, Delta_Response, Delta_Reaction, SelfReport_Focus
