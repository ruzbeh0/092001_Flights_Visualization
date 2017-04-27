# Summary
This visualization shows how the event of 09/11 affected the aviation network. 
The bubble sizes in the visualization represents total flights, while the colors 
represent cancelled flights. Each day of the visualization represents the day of the 
month. Note that after 09/11 it takes weeks for the system to return to normal.

# Design
The visualization is shown as a trip matrix, where the x axis represents destinations and
the y axis represents origins. A trip matrix format was chosen as it the most used format
to represent trips in the transportation industry.

The visualization is not intended to show flights for all airports in the US,
but to be a representation of the most important airports and show how disruptive the 
09/11 terrorist attack was to the system. 

Two different sets of information are shown: total flights and percentage of cancelled 
flights. Total flights are represented by bubble size while percentage of cancelled 
flights are represented with colors. Colors was selected for the cancelled flights since
it is the most affected variable by the terrorist event and the impact of the color change
is more noticeable.

# Feedback
04/22 - Jonathan Black: Improved visualization of cancelled flights, by representing them as colors instead
of bubble size.
04/22 - Jonathan Black: Added representation of total flights by using bubble size.
04/24 - Paul Johnson: Added legend to better explain the visualization context.
04/24 - Jacob Muller: Improved comments on index.html and design description.
04/25 - Grader 1: Removed commented coded from index.html.
04/25 - Grader 1: Updated circle to use total flights as area and not as radius.
04/25 - Grader 1: Formatted the code.
04/27 - Grader 2:

What an excellent visualisation - a real pleasure to mark!

You are extremely close to meeting specifications but there a few small things you need to change:

add some more comments to your code
look at the three design choices suggestions - in particular, I feel reader/graphic communication will be better once your date label is more prominent.
make sure you add your insights to the README summary
if you still have them, add the exact quotes from each of your feedback reviewers to the README file.

You've made some excellent design choices so far. I particularly like:

your chart choice
colour coding
use of animation
clear, accessible legends, labels and tooltips.
central dots for each bubble
There are three things which I feel could optimise reader/graphic communication further:

day label - this is such an important visual encoding that you need to make it bigger. I'd also highly recommend making it a full date for impact "1st September 2011". Here are some ideas for generating ordinal numbers.
bubble size - have you tried restricting the maximum radius to the width of each axis square? Here is a link that may help.
animation speed and loop - I would recommend stopping the animation after one loop and speeding it up a bit. It's not the individual days you are interested in but the flow throughout the month?
All of these are recommendations. The first one is required as the current label size is not very accessible for the reader, the other two are suggestions for you to implement if you feel they are appropriate. If you don't implement them then please document your reasoning in the README file.

Response: Comments added, day label size increased and readme summary updated. A
The exact quotes from the previous reviewers are not available.
The speed was increased after the first loop.
Regarding the bubble size, I made no changes since a maximum radius would make origin-
destination pairs with high total flights not very noticeable.

# Resources
https://github.com/PMSI-AlignAlytics/dimple/wiki
http://dimplejs.org/