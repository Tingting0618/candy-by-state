# candy-by-state
### Datasets
Two datasets are provided with this assessment:
- candy data (`top_halloween_candy.csv`)
- population data (`population_est2017.csv`)

### Instructions
1. Name your jupyter notebook with <firstname_candy>. For example, my notebook would be named `michael_candy.ipynb`
2. Read in the candy data and look at the top 5 rows.
3. Clean up the `top_candy_pounds`, `second_place_pounds`, and `third_place_pounds` columns by removing the "lbs" at the end and converting to a numeric type.
4. Create a visualization (your choice) to show the top 3 candies for the state of Tennessee. **Optional Bonus:** Make a widget that allows the user to choose a state and have the visualization update to show the top three candies for the chosen state.
5. Create a new column, `total_pounds`, to show the combined weight of 1st, 2nd, and 3rd place candies consumed per state.
6. Which state consumes the most of its 1st, 2nd, and 3rd place candies combined (greatest combined weight)?
7. Read in the population data and merge it with the candy data.
8. Calculate a new column, `per_capita` to show the average weight of 1st, 2nd, and 3rd place candies (combined) consumed per person in each state.
9. Create a histogram showing the distribution of `per_capita` values by state.
10. Which state has the greatest consumption of its 1st, 2nd, and 3rd place candies per capita?
11. For this state, what is the consumption per capita of *each* of the top-3 candies?
12. Find the five candies that show up most frequently (1st, 2nd, and 3rd places combined) in the dataset. Create a bar plot to show the number of times these five candies appear in the dataset.
13. Find all unique candies -- those that appear in a state's top-3 list but _do not_ appear in any other state's list. Report both the candy name and the state in whose list it appears.
