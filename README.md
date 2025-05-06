# statistics452-652-project-2-solved
**TO GET THIS SOLUTION VISIT:** [STATISTICS452-652 Project 2 Solved](https://www.ankitcodinghub.com/product/statistics452-652-project-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97982&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STATISTICS452-652 Project 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
ASSIGNMENT

The file will be a comma-separated file (csv) that contains n observations of p explanatory variables (labeled X1–Xp) and one response (Y). That’s all I’m telling you about the data.

Your job is to develop a method for predicting Y based on X. You may use any of the techniques covered in class.

DELIVERABLES

You will produce two required items and one optional item.

1. I will post a test set of explanatory variables without the response variable attached. You will return a list of predicted values, in the same order. The list should be one column of numbers with no row numbers and no column header. Use write.table(predictions, file.name, sep = “,”, row.names = F, col.names = F)

to submit your code, where predictions is the name of the vector containing your predicted values and file.name is the location on your computer where you want to

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
store the results. These will later be uploaded into a Shiny app that we will introduce later.

Look at your file before you submit it to make sure that the format is correct (and also to make sure that the predicted values are sensible!).

2. You will supply a written report of the steps you took to create your model and predictions. This gets posted to Crowdmark. Details are given below.

REPORT

Your report, which is submitted to Crowdmark, should answer these questions, as numbered below:

<ol>
<li>What models or machines did you attempt to fit? For each one, paste the R code from your program for the initial successful model fit. I want to see what you tried. For example, “fit1 = lm(y~., data=train)” is what I would list if I used multiple linear regression on all of the variables and my training data were called “train”. The answer should be a list (e.g., with bullets) of nothing but the code for each of these model fits. Don’t list code that did not run. If tuning was involved in the initial fitting process, you can can paste the function with variable names for the tuning parameters (e.g., your function might have “mtry=mm” if you looped over a variable called “mm”).</li>
<li>What process(es) did you use to evaluate and compare models and to select your final model? I am thinking of Lecture 3, specifically: Give 1-2 sentences explaining the method, the quantity, how results were turned into decisions. For example, “I used 50,000 bootstrap resamples, fit all models to each resample, and used largest training error from last resample as my best model.” (This example answer is complete, but represents something rather stupid to do…)</li>
<li>Did you tune any methods? If so, (a) what process(es) did you use to evaluate and compare models and to select your final model (i.e., I want to see an answer like to the previous question, but relating to how TUNING was done), and (b) for each method list all parameter values that were considered (e.g., “For “Blasting” I use a grid of values with A=(1, 2, 3, … , 60) and B=(0.00317, sqrt(3.14159)). For “Blooming” I used combinations of (z,γ)=(0.1, 3), (0.5, 6), and (1.1, 12) ).</li>
<li>What was your chosen prediction machine? Paste the code that produced your predicted values, including all values of tuning parameters if any, random number seeds, and explaining any variable names that are not obvious. I should be able to run your code and produce the same results (or extremely similar if randomization is used). If I try and it doesn’t work, there will be a major deduction.</li>
<li>(optional) List the variables that you believe are important. A positive bonus will be given for each correct results. A deduction will be made for each variable listed that was not important.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
The main thing here is that I should be able to see what your thought process was and whether you considered (or failed to consider) important ideas.

GRADES

Your grade will be based partly on how well your model performs, and partly on the steps you took to get there. I will compute a form of R2 between your predicted values and the test set responses. I will scale these against the best model produced by a member of the class, so this is a competition! If your R2 is only 80% as large as the best, your mark for this part will be 80%.

Your report as described above. This portion will count for 60% of your grade. The remaining 40% will come from your model’s performance.

If you supply a list of variables that are in the model, I will give a small bonus for each variable that you correctly identify. I will subtract the same amount for each variable that you incorrectly list!

FINAL COMMENTS

GOOD LUCK, HAVE FUN, and remember: in real life an employer will take action based on the results you provide them. These may be million-dollar decisions which rely extensively on YOUR expertise. This is practice…

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
