# DnD-Alignment-Chart-Visualizer
Visualizer to help determine your group's D&amp;D alignment chart. Click [here](#instructions) for instructions.

<center><img src="imgs/screenshots/example_grid.png" alt="form example" width="75%"/></center>

### Background
The original alignment charts came from the game Dungeons and Dragons, you can read more about this [here](http://easydamus.com/alignment.html). Nowadays, these alignment attributes have become largely memes, ubiquitous across social groups and topics.

<center><img src="imgs/examples/chart.png" alt="alignment chart example" width="75%"/></center>
<center><img src="imgs/examples/bread.jpg" alt="bread alignment chart example" width="75%"/></center>

### <a name="instructions"></a>Instructions

1. Create a Google form like [this one](https://docs.google.com/forms/d/e/1FAIpQLScxx_S6Qrvrc7RqJIHDrhSIVG4G8VEy7VzNsM7PsFgBhPAnkg/viewform) (screenshot available in appendix). Send to friends. 
2. Save the responses to a CSV file.
3. Open `visualizer.ipynb` and replace the CSV file path. Run the whole notebook for results! See the last cell to change the order of how each person shows up.

<!--![form creation example](imgs/screenshots/template_maker.png)
-->
### Dependencies
- Python 3.6+
- Pandas 
- Matplotlib
- Sklearn (optional for extra anonymity)

### Appendix
![form example](imgs/screenshots/template_form.png)

