<h3 style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt; text-align: center;"><span style="font-size: 13.999999999999998pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Course Final Project</span></h3>
<p>&nbsp;</p>
<p style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">This project serves as an opportunity to apply the techniques presented in the course videos through</span><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: #ffffff; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"> an end-to-end, completely reproducible research project. This assignment will contain multiple parts. You will need to write a report that resembles a typical article in a biomedical journal and includes an abstract, introduction, methods, results and discussion sections, as well as any appropriate tables/charts/graphs and a list of references (see sections 1-6 below). You will need to provide all code with useful comments written in a literate programming style (section 7). The &lsquo;report&rsquo; sections and code should be interspersed throughout a document like RMarkdown or Jupyter notebook. Finally, you will need to upload all documents relating to the project (section 7) to the class GitHub: <a href="https://classroom.github.com/a/RVSJRs4C" target="[object Object]">https://classroom.github.com/a/RVSJRs4C</a>. Keep in mind best reproducibility practices throughout the project, and see the sections below for more details and expectations.</span></p>
<p style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;">&nbsp;</p>
<ol>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Abstract (typically 250 words or less)</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Motivation: Why do we care about the problem and the results? What is the knowledge gap your work fills?</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Problem statement: What problem are you trying to solve? What is the scope of your work (a generalized approach, or for a specific situation)?</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Approach: How did you go about solving or making progress on the problem? Did you use simulation, analytic models, prototype construction, or analysis of field data for an actual product? </span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Results: What did you find? What did you answer?</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Conclusions: What are the implications of your results?</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Introduction (1-2 paragraphs)</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Project topic background and importance (more detailed than the abstract)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Short summary of previous work (literature review)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The knowledge gap your work will be filling (more detailed than the abstract)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Be sure to cite previous work where appropriate</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Methods (2-4 paragraphs with code interspersed)</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The source of the data</span><ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The date (or time period) of collection</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Method of data collection</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Sample size</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Outcome of interest (include type, i.e. binary, continuous, categorical, time to event, etc.)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">List of predictors (covariates) </span></li>
</ol></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Brief data cleaning (munging) summary</span><ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Were there missing values? How did you handle them?</span></li>
</ol></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Statistical methods used for analysis</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Results</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Include appropriate tables, charts and figures</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Report important outcome values or measurements (p-values, odds ratios, etc.)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Include all code used to generate the visuals and results</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Discussion (1-2 paragraphs)</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Discuss your findings (Did you answer your scientific question/hypothesis?)</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Include any conclusions you can make from your results and how they advance work in your field including any implications your findings will have in practice</span></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Briefly describe possible future directions this work could take</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">References</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Include a list of references and work cited in the paper</span></li>
</ol></li>
<li>
<h4><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: underline; vertical-align: baseline; white-space: pre-wrap;">Project Code</span></h4>
<ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Include a README file that details the content of each file and how to run the analysis</span><ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Document and comment all code files</span></li>
</ol></li>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Provide clean data set(s) and/or synthetic data sets for the user with variable labels and descriptions</span><ol>
<li><span style="font-size: 11pt; font-family: Avenir; color: #000000; background-color: transparent; font-weight: 400; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Upload code and all project documents to a repository</span></li>
</ol></li>
</ol></li>
</ol>
