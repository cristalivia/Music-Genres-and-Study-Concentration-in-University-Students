# Music Genres and Study Concentration in University Students
This project explores the relationship between music genres and students’ concentration during study sessions. The dataset was collected from students of Class of B27, BINUS University (Kemanggisan Campus) through an online survey. The analysis investigates whether listening to music helps students focus, what genres are most effective, and how music influences motivation, stress levels, and productivity.

## Approach

- 164 survey responses from BINUS University students (B27), reduced to 161 valid entries.
- Removed duplicates, irrelevant columns, and non-B27 responses.
-Visualized demographics, study habits, music preferences, and Likert-scale responses.
- Normalized music genres, cleaned open-ended answers, and generated word clouds.
- Explored relationships between concentration, motivation, stress reduction, and productivity.
  
## Key Findings
- Majority of students (72.9%) who listen to music while studying also recommend it to others.
- The most frequently chosen genres (after normalization) are Pop (dominant), Jazz, Lofi, Classic, and Instrumental.
- Students generally prefer lyric-free music (Lofi, Classical) because it supports concentration.
- Correlation analysis shows that motivation strongly correlates with both task completion (+0.55) and concentration (+0.49). Also, stress reduction correlates with mood stability (+0.41).
- Music’s positive effect is consistent in individual study tasks, but results are mixed in group discussions (some students feel disturbed).

## Conclusion
- Music has a positive relationship with concentration in student learning, especially through psychological factors like motivation and stress reduction.
- Certain genres (especially lyric-free ones) are more effective in maintaining focus compared to lyrical music.
- While preferences vary, Pop remains the most popular genre overall among BINUS University students.
- The analysis supports the idea that music can serve not just as entertainment but also as a study aid that improves concentration, emotional balance, and productivity. However, the effectiveness of music is beneficial for solo study, but less conclusive for collaborative learning.

## Tools & Frameworks 
- Python: (Pandas, NumPy)
- Visualization: (Matplotlib, Seaborn, WordCloud)
- Text Preprocessing: NLTK
- Feature extraction: TF-IDF (scikit-learn_
