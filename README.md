# Netflix Data Analysis

## Project Highlights
- **Data Cleaning & Preprocessing**: 
  - Cleaned and preprocessed the Netflix dataset by handling missing values, removing duplicates, and reformatting date columns.
  - Ensured the dataset was ready for analysis with minimal data inconsistencies.

- **Exploratory Data Analysis (EDA)**: 
  - Performed detailed analysis to uncover insights, including:
    - Patterns in content releases across genres and countries.
    - Viewer ratings and their distribution.
    - Genre distributions and country-specific trends.
    - Director performance and popular cast members.
  
- **Data Visualization**:
  - Visualized key patterns using tools like Matplotlib to present trends in Netflix’s movie and TV show catalog.
  - Used statistical methods to identify significant content trends.

---

## Dataset Overview
### Dataset Snapshot
![Netflix Dataset Snapshot](https://github.com/user-attachments/assets/5afcd8c0-3975-49bf-8c5d-db034e30e892)

### Column Names
```plaintext
Index(['Show_Id', 'Category', 'Title', 'Director', 'Cast', 'Country', 'Release_Date', 'Rating', 'Duration', 'Type', 'Description'], dtype='object')


and details as- 
RangeIndex: 7789 entries, 0 to 7788
Data columns (total 11 columns):
 #   Column        Non-Null Count  Dtype 
---  ------        --------------  ----- 
 0   Show_Id       7789 non-null   object
 1   Category      7789 non-null   object
 2   Title         7789 non-null   object
 3   Director      5401 non-null   object
 4   Cast          7071 non-null   object
 5   Country       7282 non-null   object
 6   Release_Date  7779 non-null   object
 7   Rating        7782 non-null   object
 8   Duration      7789 non-null   object
 9   Type          7789 non-null   object
 10  Description   7789 non-null   object
dtypes: object(11)
memory usage: 669.5+ KB
```


- rough idea of frequency of null values from graph 
![image](https://github.com/user-attachments/assets/76c929d8-c84b-461a-a49b-7a69ad4d0956)

