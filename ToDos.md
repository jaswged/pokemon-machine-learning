# ToDos

Reread in csv and set index right away.

## EDA

- [x] In combats convert `Winner` column to be first or second. I.E. Not the number
- [x] Remove Name. Cardinality too high
- [x] Convert types to categories and 1-hot encode
- [x] Convert ids to smaller ints to save space `df['age'].astype('int8')`
- [x] Check combat winners to make sure you have an even distribution
  - 23_601/ 50_000 = 47.2% first wins
  - Drop extra rows to even out classes. `first_wins`

## Thoughts

Or Rather things to try

- Remove vs keep `Legendary`. Other stats might already show who's legendary.
- Remove `Generation` number? Shouldn't matter unless got stronger over time overall
- Remove type2 initially. No way to impute it? One hot encode?

## Modelling

- Do the map of different models to test out several at once
- Predict first_wins for second set of values
