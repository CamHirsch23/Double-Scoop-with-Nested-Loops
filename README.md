# Question 1 
# Task 1 

import random

moods = ["Happy", "Sad", "Energetic", "Calm"]

for day in range(1, 8):
    mood = random.choice(moods)
    print(f"On {day}, you were feeling {mood}.")
    
# Question 2 
# Task 1 

import random

days_of_week = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"]
times_of_day = ["morning", "afternoon", "evening"]
moods = ["Happy", "Sad", "Energetic", "Calm", "Tired", "Excited"]

for day in days_of_week:
    for time in times_of_day:
        mood = random.choice(moods)
        print(f"On {day} {time}, you were {mood}.")
