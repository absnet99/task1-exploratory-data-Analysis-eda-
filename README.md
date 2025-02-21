# task1-exploratory-data-Analysis-eda-
codtech it solustion
# start 
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

df = pd.read_csv('D:\\download\\arkham_txns.csv')
print(df.describe())
sns.heatmap(df.corr(), annot=True)
plt.show()

