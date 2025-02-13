| [home page]([https://cmustudent.github.io/tswd-portfolio-templates/](https://serena-xue.github.io/2025Spring-Telling-Stories-with-Data/)) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |





# Title: Humans vs. Animals: Gender Differences

## Step one: the visualization

The original data visualization is from: [](https://today.yougov.com/society/articles/35852-lions-and-tigers-and-bears-what-animal-would-win-f).
A interesting YouGov survey studied which animals Americans think would win imagined battles, both among themselves and against unarmed humans. Elephants and rhinos were ranked highest in animal-versus-animal matchups. Americans are confident facing smaller animals, while lack confidence facing bigger ones. There are also some differences between genders: men are more likely to think they could defeat specific animals like wolves and kangaroos.

## Step two: the critique
The original visualization (viz) consists of 3 parts: animals vs. animals, animals vs. human beings and gender difference. 

![](https://ygo-assets-websites-editorial-emea.yougov.net/images/Animal20fights20chart20120v2.format-webp.webp)

For the first viz, it's quite creative and impressive to put photos of considered to be the most strongest animals on the top. These 5 photos seem to be the top 5 strongest, while not. Use a podium to indicate top 3 considered to be strongest and highlight other interesting animals in the list may be better. This causes confusion. 

![](https://ygo-assets-websites-editorial-emea.yougov.net/images/Animal20fights202-01.format-webp.webp)

The second viz is good, with suitable layouts and title with conclusion, even though the photos seem meaningless. Better to remove the photos and highlight interesting animals discussed below (such as grizzly bear and lions).

<div>
    <iframe
            src="https://datawrapper.dwcdn.net/wadD1/3/"
            style="min-width: 100%;"></iframe>
</div>

For the third viz, a dumbbell chart is for gender difference. Good for showing difference, but it would be more intuitive for the color saturation to change based on the degree of difference.

## Step three: Sketch a solution

The audience are netizens who have nothing better to do than to brush up on their online posts and have somewhat interest in social science and animals. I consider a dashboard to represent the 3 viz. Left part is for animal vs. animal and right part is for animal vs. human being.

First is on the left, with a title "Which animals are the most UNBEATABLE in a fight". I use a podium to showcase the top 3 strongest animals: with photos on it, no names on the podium, rating added as badges. Below that, the list of other animals remain the same, but with font size in descending order of support. The theme color is red and yellow.

The second viz is on the top right, with a title "Which animals could you beat in a fight". The bar chart layout remains the same, descending order of rating. Adding photos or icons of animals to the top of bars to make the picture more impressive. The theme color is green.

The third vis is on the bottom right, with a title same as original one: "Compared to women, men feel most able to take on medium-sized dogs and geese". All elements are the same except applying high-matured colors to emphasized animals.

## Step four: Test the solution

Interviewees: MAM, with 2-year SDE experience, MISM

*We used a more open-ended discussion where everyone's answers complemented each other, so there was no clear distinction.*

- Can you tell me what you think this is?
  - What animals are strongest, against animals and against human beings. Perceived differences between men and women.
- Is there anything you find surprising or confusing?
  - So many photos, dazzled.
  - A podium for the top 3 strongest animals is a great idea.
- Is there anything you would change or do differently?
  - Dumbbell chart is not clear enough: labels are far from values, better to put them more closely. A stacked bar plot or a diverging bar plot are more helpful.
  - Topics are not focused. Better to focus on animals vs. animals and animals vs. human beings. The other topic, difference between men's feeling and women's feeling, is less attractive. Two tabs for contrast and add titles for them are more clear to understand.
  - Better not to replace names of anminals by photos.

Synthesis: 

Focus on one topic. Do not use so many photos. Dumbbell chart is not clear enough, better to use a diverging bar plot.

## Step five: build the solution

<div class="tableauPlaceholder" id="viz1739405504297" style="position: relative;">
    <noscript>
        <a href="#"><img alt="Human vs Animal Fight " src="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hu&#47;HumanvsAnimalFight_17394051436560&#47;HumanvsAnimalFight&#47;1_rss.png" style="border: none;" /></a>
    </noscript>
    <object class="tableauViz" style="display: none;">
        <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" /> <param name="embed_code_version" value="3" /> <param name="site_root" value="" />
        <param name="name" value="HumanvsAnimalFight_17394051436560&#47;HumanvsAnimalFight" /><param name="tabs" value="no" /><param name="toolbar" value="yes" />
        <param name="static_image" value="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hu&#47;HumanvsAnimalFight_17394051436560&#47;HumanvsAnimalFight&#47;1.png" /> <param name="animate_transition" value="yes" />
        <param name="display_static_image" value="yes" /><param name="display_spinner" value="yes" /><param name="display_overlay" value="yes" /><param name="display_count" value="yes" /><param name="language" value="zh-CN" />
        <param name="filter" value="publish=yes" />
    </object>
</div>
<script type="text/javascript">
    var divElement = document.getElementById("viz1739405504297");
    var vizElement = divElement.getElementsByTagName("object")[0];
    if (divElement.offsetWidth > 800) {
        vizElement.style.width = "1366px";
        vizElement.style.height = "795px";
    } else if (divElement.offsetWidth > 500) {
        vizElement.style.width = "1366px";
        vizElement.style.height = "795px";
    } else {
        vizElement.style.width = "100%";
        vizElement.style.height = "1027px";
    }
    var scriptElement = document.createElement("script");
    scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class="tableauPlaceholder" id="viz1739405504297" style="position: relative; width: 100%; padding-bottom: 56.25%;">  <!-- 16:9 aspect ratio -->
    <noscript>
        <a href="#"><img alt="Human vs Animal Fight " src="https://public.tableau.com/static/images/Hu/HumanvsAnimalFight_17394051436560/HumanvsAnimalFight/1_rss.png" style="border: none;" /></a>
    </noscript>
    <object class="tableauViz" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
        <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
        <param name="embed_code_version" value="3" />
        <param name="site_root" value="" />
        <param name="name" value="HumanvsAnimalFight_17394051436560&#47;HumanvsAnimalFight" />
        <param name="tabs" value="no" />
        <param name="toolbar" value="yes" />
        <param name="static_image" value="https://public.tableau.com/static/images/Hu/HumanvsAnimalFight_17394051436560/HumanvsAnimalFight/1.png" />
        <param name="animate_transition" value="yes" />
        <param name="display_static_image" value="yes" />
        <param name="display_spinner" value="yes" />
        <param name="display_overlay" value="yes" />
        <param name="display_count" value="yes" />
        <param name="language" value="zh-CN" />
        <param name="filter" value="publish=yes" />
        <param name='device' value='default' />  <!--  Add this line for responsiveness -->
    </object>
</div>
<script type="text/javascript">
    var divElement = document.getElementById("viz1739405504297");
    var vizElement = divElement.getElementsByTagName("object")[0];
    // Remove the original JavaScript size adjustments.  Tableau handles it.
    var scriptElement = document.createElement("script");
    scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


The audience are netizens who have nothing better to do than to brush up on their online posts and have somewhat interest in social science and animals. I focus on gender perspective difference on "what animals can I beat". Bars with high difference (>10%) are highlighted. I intended to add some photos or icons, but the graph seems like not suitable for them. To be more impressive and more close to topic, I pick Impact as title font and Rotonto as body font.

A diverging bar plot is not supported in basic funcions of Tableau. I tried for a long time on how to acchive it with two bar plots and make y-axis at the middle. Finally, I managed to achieve it with a dashboard.

## References
[Rumble in the jungle: what animals would win in a fight?](https://today.yougov.com/society/articles/35852-lions-and-tigers-and-bears-what-animal-would-win-f)

## AI acknowledgements
Use DeepSeek to redesign the title: I gave AI: WHAT ANIMALS CAN YOU BEAT? GAP BETWEEN MEN AND WOMEN, ask AI to come up with more brief and interesting titles. AI recommended some and I picked "Humans vs. Animals: Gender Differences".
