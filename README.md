# bike-theft-plot
A Jupyter notebook repository for plotting reported bike theft (bikewise.org) from January 1, 2018 to April 3, 2020.

## **Introduction**<br>
```plot_bikewise.ipynb``` and ```gif_generator.ipynb``` complement each other in:
1) Gathering line plots of reported bike thefts from [Bikewise](https://www.bikewise.org/).
2) Converting these figures to a gif.
<br><br>
<p align = 'center'>
<img src=https://i.imgur.com/RIcHkby.gif alt="2018 - 2020 bike theft gif"
    width=600><br>
</p>

## **Python Setup**<br>
This script requires Python 3.5 and above. Please see ```requirements.txt``` for required Python libraries. Clone this repository and use ```pip``` to install the necessary libraries, like this:<br><br>
```pip install -r requirements.txt```


## **Running the Notebooks**<br>
Run ```plot_bikewise.ipynb``` entirely. Figures will accumulate in the ```./figs``` directory.
<br>

Then, run the entirety of ```gif_generator.ipynb```. Provide an appropriate name for your gif when prompted in ```main()```. This will create a .gif file of your .png images in the ```./gifs``` directory.
<br>
<p align = 'left'>
<img src=https://i.imgur.com/USkyq0P.png alt="GIF progress bar"
    width=400>
</p>

## **Notes**<br>
A .png file can range from 30kb to >200kb in size. Accumulating thousands of figures can lead to a large .gif file. For example, ~1000 figures could lead to a ~ 200 MB gif image.

Please let me know if you have any questions.

***Fin***


