# AI-Software-Development
Artificial Intelligent I'm a new student even though I know basics about python
import pandas as nathi

df_loaded = nathi.read_csv("C:/Users/Initium VS12/Downloads/annual-enterprise-survey-2023-financial-year-provisional.csv")
print(df_loaded)
import pandas as nathi

data = {
    'Name': ['Alice', 'Bob', 'Charlie', 'David', 'Eva'],
    'Score': [85, 92, 88, 76, 95]
}

df = pd.DataFrame(data)
min_max =df.max()
print(df )
print()
print('this is the maximum ' + str(min_max))
na_values= data_frame[data_frame["SCHEDULED_DEPARTURE"].isna() & data_frame['SCHEDULED_TIME'].isna()].isna()
na_values.hist(bins=60, figsize=(20, 15))
