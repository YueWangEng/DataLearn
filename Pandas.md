# Pandas

1. Pandas通常会自动添加索引列，使用index_col=0，直接将第一列作为索引，不额外添加列。  
 
2. set.option()函数，用于显示设置.   
1) pd.get_option(“display.max_columns”) 获取最大显示列数，按字段计.    
2) pd.get_option(“display.width”) 获取数据显示区域的宽度，以总字符数计算。

3. 对轴axis=0和axis=1的理解
1) axis = 1，指的是沿着行求所有列,　相当于axis='columns'
2) axis = 0，指的是沿着列求所有行,　相当于axis='row'

4. Pandas中nan值可以为除数，结果依旧为nan.
