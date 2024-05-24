### Month 1: Advanced Data Manipulation and Visualization
**1.1 Advanced Pandas and Data Wrangling**
- pandas.head()
- pandas.tail()
- We can use to separate smaller like: h= pandas.head(10) then h.head()
- can go to each column as. h['title'], h['year'] then we can have operation like h['year'] // 10 * 10
- We can use (.) operation like h.title, h.year (remember use lowercase and dont have any blank space)
- We can comparision like: h.year > 1986
- We can filter like: h[h.year > 1986] 
- Use logical with and(&) and or(|)
- Use series: with n is column

h = cast.head()
h = h[h.n.notnull()]

- Use with .str. method:
h[h.title.str.startswith('S')]
- Sort and plot: titles.year.value_counts().sort_index().plot()
- Customize: x, y, kind
c = cast
#c = c[c.character == 'Guests']
#c.plot(x='year', y='n', kind='scatter')

**1.2 Data Visualization**
- **Advanced Matplotlib and Seaborn**:
- **Plotly and Dash**:

