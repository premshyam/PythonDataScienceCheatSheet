# PythonDataScienceCheatSheet

Cheat sheet containing popular functions and commands used in data science.

## Seaborn

### Heatmap

```
sns.heatmap(df[["column", "names"]].corr(), annot=True, cmap="colorOfYourChoice")
```

### Boxplot

```
sns.boxplot(data=df, x="categoricalColumn", y="numericalColumn")
```

## Pandas

```
df["newColumn"]=pd.cut(x=df.column, bins=[], labels=[])
```

```
#accumulator can be functions such as mean median mode sum
df.groupby("columnName")["columnName"].accumulator()
```

```
df.groupby("columnName")["columnName"].aggregate(["mean", "median", "userDefinedFunction"])
```
