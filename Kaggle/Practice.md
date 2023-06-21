# the difficult practices

1. Pandas
   1) 3.6, 3.7
  
2. 对df增加一列，列名star
   reviews.loc[:,'star'] = 列
   ```
   def star_checking(row):
    if row.country == 'Canada':
        return 3
    else:
        if row.points >= 95:
            return 3
        elif row.points < 85:
            return 1
        else:
            return 2     
    #star_ratings = reviews.apply(star_checking, axis=1)
    reviews.loc[:,'star'] = reviews.apply(star_checking, axis=1)
    ```
