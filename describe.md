<div class="Markdown base-markdown base-markdown_with-gallery base-markdown markdown markdown_size_normal markdown_type_theory theory-viewer__markdown theory-viewer__markdown_flexible big-theory"><h2>Integrated Project</h2><div class="paragraph">Congratulations! You’ve officially completed the first part of the course on the interactive platform. Now it's time to bring together all you've learned so far in your first integrated project, a real-life analytical case study.</div><div class="paragraph">When you finish the project, send your work to the project reviewer for assessment. They’ll give you feedback within 24 hours. Use the feedback to make changes, then send the new version back to the project reviewer.</div><div class="paragraph">You might get further feedback on the new version. This is completely normal. It’s not uncommon to go through several cycles of feedback and revision.</div><div class="paragraph">Your project will be considered complete once the project reviewer approves it.</div><h2>Project description</h2><div class="paragraph">You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.</div><div class="paragraph">In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017. </div><div class="paragraph">(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2017 sales based on data from 2016.)</div><div class="paragraph">The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.</div><h3>Instructions for completing the project</h3><div class="paragraph paragraph_has-one-child"><strong>Step 1. Open the data file and study the general information</strong></div><div class="paragraph">File path:</div><div class="paragraph"><em>/datasets/games.csv</em> . <a href="https://practicum-content.s3.us-west-1.amazonaws.com/datasets/moved_games.csv">Download dataset</a></div><div class="paragraph paragraph_has-one-child"><strong>Step 2. Prepare the data</strong></div><ul><li>Replace the column names (make them lowercase).</li><li>Convert the data to the required types.</li><li>Describe the columns where the data types have been changed and why.</li><li>If necessary, decide how to deal with missing values:
  <ul><li>Explain why you filled in the missing values as you did or why you decided to leave them blank.</li><li>Why do you think the values are missing? Give possible reasons.</li><li>Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases.</li></ul></li><li>Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column.</li></ul><div class="paragraph paragraph_has-one-child"><strong>Step 3. Analyze the data</strong></div><ul><li>Look at how many games were released in different years. Is the data for every period significant?</li><li>Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?</li><li>Determine what period you should take data for<strong>.</strong> To do so, look at your answers to the previous questions. The data should allow you to build a prognosis for 2017.</li><li>Work only with the data that you've decided is relevant. Disregard the data for previous years.</li><li>Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.</li><li>Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.</li><li>Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.</li><li>Keeping your conclusions in mind, compare the sales of the same games on other platforms.</li><li>Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?</li></ul><div class="paragraph paragraph_has-one-child"><strong>Step 4. Create a user profile for each region</strong></div><div class="paragraph">For each region (NA, EU, JP), determine:</div><ul><li>The top five platforms. Describe variations in their market shares from region to region.</li><li>The top five genres. Explain the difference.</li><li>Do ESRB ratings affect sales in individual regions?</li></ul><div class="paragraph paragraph_has-one-child"><strong>Step 5. Test the following hypotheses:</strong></div><div class="paragraph">—Average user ratings of the Xbox One and PC platforms are the same. </div><div class="paragraph">—Average user ratings for the Action and Sports genres are different.</div><div class="paragraph">Set the <em>alpha</em> threshold value yourself.</div><div class="paragraph">Explain:</div><div class="paragraph paragraph_has-one-child">—How you formulated the null and alternative hypotheses </div><div class="paragraph">—What significance level you chose to test the hypotheses, and why</div><div class="paragraph paragraph_has-one-child"><strong>Step 6. Write a general conclusion</strong></div><div class="paragraph"><strong>Format:</strong> Complete the task in the Jupyter Notebook. Insert the programming code in the <em>code</em> cells and text explanations in the <em>markdown</em> cells. Apply formatting and add headings.</div><h3>Data description</h3><div class="paragraph">—<em>Name</em> </div><div class="paragraph">—<em>Platform</em> </div><div class="paragraph">—<em>Year_of_Release</em> </div><div class="paragraph">—<em>Genre</em> </div><div class="paragraph">—<em>NA_sales</em> (North American sales in USD million) </div><div class="paragraph">—<em>EU_sales</em> (sales in Europe in USD million) </div><div class="paragraph">—<em>JP_sales</em> (sales in Japan in USD million) </div><div class="paragraph">—<em>Other_sales</em> (sales in other countries in USD million) </div><div class="paragraph">—<em>Critic_Score</em> (maximum of 100) </div><div class="paragraph">—<em>User_Score</em> (maximum of 10) </div><div class="paragraph">—<em>Rating</em> (ESRB)</div><div class="paragraph">Data for 2016 may be incomplete.</div><h2>How will my project be evaluated?</h2><div class="paragraph">Read these project assessment criteria carefully before you get to work.</div><div class="paragraph">Here’s what project reviewers will be looking at when evaluating your project:</div><ul><li>How do you describe the problems you identify in the data?</li><li>How do you prepare a dataset for analysis?</li><li>How do you build distribution graphs and how do you explain them?</li><li>How do you calculate standard deviation and variance?</li><li>Do you formulate alternative and null hypotheses?</li><li>What methods do you apply when testing them?</li><li>Do you explain the results of your hypothesis tests?</li><li>Do you follow the project structure and keep your code neat and comprehensible?</li><li>Which conclusions do you reach?</li><li>Did you leave clear, relevant comments at each step?</li></ul><div class="paragraph">Everything you need to complete this project is in the takeaway sheets and summaries from previous chapters.</div><div class="paragraph">Good luck!</div></div>