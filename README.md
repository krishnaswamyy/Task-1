 import pandas as pd

# Load dataset
df = pd.read_csv("train.csv")

# Display first rows
df.head()

# Dataset shape
df.shape

# Dataset information
df.info()

# Statistical summary
df.describe()

# Missing values
df.isnull().sum()

# Target variable distribution
df['Survived'].value_counts()
