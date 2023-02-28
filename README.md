# The-Sunken-Forest-of-Lake-Tovel
-WORK IN PROGRESS- A study regarding Lake Tovel, an alpine lake in Trentino, Italy. The unique feat of the lake is the "Sunken Forest", consisting of several trees laying on the bottom of the lake and perfectly preserved. The goal of this study is to predict temperature changes in the future, in order to establish wether the Sunken Forest be in jeopardy.

Non-profit diver organisation “Tovel Fellowship” has collected a fair amount of data with hundreds of immersions in the lake. They asked for my help in order to gain insight from said data. Unfortunately, I only have the data from the last 3 years and I am waiting for the rest of the csv files.

Here are the steps I took

I thought about the problem and decided to opt for a numerical approach. By confronting my thoughts with the diver association, it turned out that the most important data were those collected between 9 and 30 meters depth.
I analyzed the data, finding three fundamental variables: temperature, depth(m) and time
I cleaned the first dataframe from unnecessary columns and NaN rows, and I included only the depths I needed, grouping them in ranges. For this purpose I built a pipeline composed of several custom functions, in order to hugely speed up the data preparation process for the following dataframes.
To better visualize any temperature trend over time, I used both bar and line charts. I noticed an upward trend, but the data in my possession were still too few.

I opted for a linear regression model. I built my model, trained it and tested it. 

Since the data are quite discontinuous, I am currently waiting for The Tovel Fellowship to feed me with their remaining data and proceed with the study
