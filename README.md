# Urn problems in probability
An *urn problem* is an exercise that involves questions about probability properties when extracting balls of various colors from one or more urns. For example, we may ask questions about the probability of certain sequences of extractions or about the inference of the proportion of balls of each color. We could also consider many different experimental settings (replacement vs. non-replacement after each draw, number of urns, number of ball colors, etc.).

Here, we will focus on the analysis via simulation of the convergence properties of the proportion of balls of one color under different rules. We will consider a single urn where we initially place a number $a$ of white balls and a number $b$ of black balls. Each time, we draw one ball and return it to the urn. However, depending on the type of ball drawn, we will add new balls to the urn according to some rule. After a large number of extractions and simulations, we will see where the proportion of white balls converges.

4 rules will be considered separately. We draw a ball, return it to the urn and then, we apply one of the following rules:

**Rule A:** If a white ball was drawn, a black ball is added to the urn. If a black ball was drawn, a white ball is added to the urn.

**Rule B:** The same total number of balls (6) is always added after each draw regardless of the color obtained. If a white ball was drawn, four white balls and two black balls are added. If a black ball was drawn, five white balls and one black ball are added.

**Rule C:** A different amount of balls is added to the urn after each extraction depending on the color obtained. If a white ball was drawn, two white balls and three black balls are added (5 in total). If a black ball was drawn, three white balls and four black balls are added (7 in total).

**Rule D:** (Pólya's urn) If a white ball was drawn, an extra white ball is added to the urn. If a black ball was drawn, an extra black ball is added to the urn.

To view the material on GitHub, click on the file *urn-problems.md*, whose contents are rendered correctly on this platform. If you want to run the code, download the notebook *urn-problems.Rmd* containing the R code chunks.
