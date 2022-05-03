# matplotlib_seaborn_template


This notebook is to develop a pipeline for generating plots using seaborn. Fig sizes/fonts/axises are tuned for paper submissions.
So far we have covered templates for the following plots:

violinplot

histplot

barplot with confidence intervals

barplot with confidence intervals

Also this [webpage](https://www.color-hex.com/color-palettes/popular.php) has provided some cool palates for graph plots:

The example below shows how to change the palette into high contrasts:  ['#ff3f3f', '#ffcc06',  '#0a9ad7', '#9ad70a', '#d70a9a']
 
    cmap = ['#ff3f3f', '#ffcc06',  '#0a9ad7', '#9ad70a', '#d70a9a']
    
    ax = sns.barplot(x="day", y="total_bill", hue="sex", data=tips, errwidth=7, palette=cmap)
                 
