Title:  How to showcase your Apache Spark skills
Subtitle:    Selecting good code projects
Project:     Learn Apache Spark
Author:      Mark Plutowski
Affiliation: Plutoware Delimited
Web:         https://pluteski.github.io
Date:        2018-07-29


# How to spotlight your Apache Spark skills 

<img align="right" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/L4.UI.DAG.png" alt="Spark UI DAG" width="230px"
/>
How do you prove your capability as a Apache Spark data scientist when you don’t have much to show? Perhaps this is because you don’t have much experience. Perhaps it is because the work you do cannot be shown. 
You may have done impressive work, but have nothing to share because most developers work for companies that don’t publish their code as open source. 

In my long career 
as data scientist and machine learning developer, I have learned many useful lessons for organizing information and presenting it effectively. 
I have created online courses to help the aspiring [data scientist](https://learn-apache-spark.thinkific.com/courses/spark-sql) 
and [machine learning developer](https://learn-apache-spark.thinkific.com/courses/sparkml-features). 
This article is going to delve more into how to present yourself. 
I am going to give you some tips for bringing your skills out of the dark and into the light. 

## Publish your work
Publishing a code project is a great way to introduce yourself to an interviewer. This also provides the interviewer 
with ample talking points for various styles of interview questions. Doing this makes the interviewers job easier. 
You are giving them context on what you already know. 
You also provide them with talking points for initiating discussion. 
Interviewers in the software industry are often stretched thin. 
Making their job easier puts them into a better mood. 
This also demonstrates your preparedness. This type of preparation can be helpful for many types of interview questions, including behavioral questions, situational questions, coding challenges, and system design challenges. 

## Show what you know
In this article I will show you how you can showcase your Apache Spark skills. I’ll show you how publishing your work in a self-contained manner using informative visualizations can separate your from the pack.  I’ll also show how to select a coding project that demonstrates useful skills that are immediately applicable in a production setting.  Furthermore, in setting this up you acquire skills that are valuable for the coding challenge portion of the interview. 

## Know what you show
To utilize this approach effectively, you must be intimately familiar with every line of content in your repo. The best way to achieve this is to create an original work of your own design, developed from start to finish by yourself. Once you get started this may not take as long as you expect. On the other hand, there may be steps that blossom into much more time-intensive investment than you expected.  That's actually ok -- it gives you something interesting to explain when discussing your process. 

## Hone your edge, gain a new one
Someone who has well organized and nontrivial open source code will be prioritised over other similarly experienced candidates because their competencies are easier to evaluate.  By providing visibility you simplify the job of the recruiters and interviewers, while simultaneously preparing yourself for the interview. Even better, you may learn skills that will be useful on the job.

## What we will cover
In the first part of this article, I'll show an example code repository.
In the second part I'll discuss strategy for selecting a code project. 
In the third part I'll give some ideas for a coding project suitable for 
Apache Spark. 
In the fourth part I'll show how you can supplement this approach with 
visualizations obtained from Apache Spark log output and the Spark UI.

# Example repo
As an example, take 
[this python repo](https://github.com/pluteski/first2017mp) that I published on github. 
I developed this during my role as a mentor for a robotics team to teach students how to use a code repository.
The repo uses [the readme](https://github.com/pluteski/first2017mp/blob/master/README.md) to explain the project at a high level manner while also 
giving a developer a quick start guide. 
Often overlooked, [the repo wiki](https://github.com/pluteski/first2017mp/wiki)
is a great way to elaborate further in breadth as well as depth.

The wiki is a great place to provide visuals that allow readers to quickly get a sense of what your project does. 
[Figure 1](https://github.com/pluteski/first2017mp/raw/master/images/stage3_paths_ne.png) 
and [Figure 2](https://github.com/pluteski/first2017mp/raw/master/images/stage2_fleur_de_lis.png) 
are two of the more visually appealing visualizations from this project. 
They give the reader an idea at a glance of what is being done and how, and draw the reader in to learn more.

<p align="center">
<img src="https://github.com/pluteski/first2017mp/raw/master/images/stage2_fleur_de_lis.png" alt="Fleur-de-lis search pattern (copyright Mark E Plutowski)" width="400px"/>
<br>
<b>Figure 1. Fleur-de-lis search pattern </b>
</p>

Figure 1 shows a fleur-de-lis search pattern used by an algorithm that I developed for a simple offline geometric planner. Not only is it an appealing visualization, it also illustrates a key step in the algorithm. 

<p align="center">
<img src="https://github.com/pluteski/first2017mp/raw/master/images/stage3_paths_ne.png" alt="Sample trajectories (copyright Mark E Plutowski)" width="400px"/>
<br>
<b>Figure 2 sample trajectories found by the planner</b>
</p>

Figure 2 shows trajectories discovered by the planner for one of the goal states overlaid on a depiction of the playing field. 

## Displaying depth and breadth
Whereas space in a resume is limited, the wikified repo format 
provides ample space to emphasize your abilities to arbitrary breadth and depth. 

You can use the [readme page](https://github.com/pluteski/first2017mp/blob/master/README.md) or [the wiki home page](https://github.com/pluteski/first2017mp/wiki) to link to other pages that provide context for what you were trying to accomplish, and why your approach is sensible. 

For example, the [Background](https://github.com/pluteski/first2017mp/wiki/Background) page of my repo gives a brief primer on Alternative Approaches, and Implementation Steps. The next sections explain the why, what, and how of the project. You could use something similar to demonstrate your depth of understanding of specific techniques. The [Related Approaches page](https://github.com/pluteski/first2017mp/wiki/RelatedApproaches) 
of the repo gives a brief primer on specific alternative approaches that were considered, which one was selected, and why. You could use this to demonstrate your breadth of understanding of a field of interest.  The [Planning Stages page](https://github.com/pluteski/first2017mp/wiki/Planning-Stages) describes what the code actually does.  It gives links to python notebooks containing visualizations, such as [this sample trajectories notebook](https://github.com/pluteski/first2017mp/blob/master/sample_trajectories.ipynb). This allows an interviewer to review your code and see how it behaves on actual data, because when you check in the notebook, you also check in the results from the latest run. 

Notebooks allow you to blend code and visuals and tell the story behind your code without cluttering up the code itself. This [test page](https://github.com/pluteski/first2017mp/blob/master/test.ipynb) from my repo gives data from tests designed to simulate the code under realistic conditions and demonstrate its use of compute resources. This type of presentation demonstrates a data-driven mindset and indicates that you know how to test your code rigorously. 

## Customize to your needs

You probably wouldn’t need all of these pages. I did them all because it was instructive for the robot team participants. My comprehensive approach serves to illustrate the various types of information that may can be shown.  You must decide for yourself which ones are relevant for showcasing your competencies.


Most readers may not delve deep, but for those that do are able to glean more information about your qualifications. You can also refer back to this during the interview. On the other hand, if your intended role values brevity more than comprehensive coverage and succinctness is an important element of style, then you should go for that instead.

Using these assets an interviewer could explore multiple aspects of your skill as a developer, such as your ability to do the following:

* Decompose a complex problem
* Design a multifacted system
* Set up a new code repository
* Organize a code repository
* Write performant code
* Visualize key results
* Communicate effectively 

As already stated but which bears repeating, this eases the burden on the interviewer.  Providing these assets gives the interviewer opportunity to derive behavioral questions. It conversely gives you ample content you can use to answer those behavioral questions. Use the STAR technique, by describing the situation (**S**), distilling it down to a single task (**T**), and the key action (**A**) you used to solve it, concluding with the result (**R**). 

It also provides code screeners with code examples they can use as a starting point for more in depth exploration of your skills. Instead of selecting a random problem for the coding challenge, they may choose one that is within your wheelhouse. 

## Showcasing your repo

Review code repositories relevant to your own goals and learn how to distinguish effective ones from half-baked ones. Pick one or two to serve as a role model for your own design.

# Choosing a coding project 

Many new developers make the mistake of picking code projects similar to what they encountered in an academic setting. These are often not relevant to a real-world job as a commercial software developer, because they exclude some of the messier aspects of a commercial application, such as cleansing a dataset, putting data into a form that can be utilized by an efficient algorithm, testing edge cases, and analyzing complex results. Interviewers want to see that you possess knowledge and can learn quickly, but even better if you are familiar with heterogeneous aspects of a development task. A well known AI researcher once said that in the university setting they spent 20% of their time prepping the dataset and 80% on the algorithm development, whereas in a commercial setting this ratio was reversed.

## Choose well
Your mission is to showcase your ability to apply Apache Spark to a nontrivial real dataset. As a general rule of thumb -- if you didn’t need to perform any data cleansing or preprocessing on the dataset, the data wasn’t messy enough to be realistic.  If your solution ran in a few seconds it was not challenging enough to test your algorithms. If it didn’t exhaust at least half of the memory available to your system and run the fan to cool the cpu, then you probably could increase the complexity of the task, either by tackling a larger dataset, or by subjecting the dataset to on a more challenging analysis.

>    "I find that the best portfolio projects are less about doing fancy 
>    modeling and more about working with interesting data." - [Advice on 
>    Building Data Portfolio Projects](https://medium.com/@jasonkgoodman/
>    advice-on-building-data-portfolio-projects-c5f96d8a0627), J.Goodman

The key to choosing a code project to show in your portfolio is authenticity. 
If this is not a true representation of what you can do, it can backfire. 
You want the reader to know that this is an original creation of your own making. 

# Ideas for a coding project 

## Migrate an existing solution to Spark 
In this case, there might already be an existing solution for solving a problem.  Your mission is to migrate the solution to Apache Spark and compare the results. Many such datasets and associated solutions that you can use as a point of departure exist online. I performed a [similar exercise myself (2016)](http://qr.ae/TUIbIH), migrating a proof-of-concept classification application from scikit/numpy to PySpark, converting it into a stacked ensemble, and tuning it to be able to handle sixty thousand input features and five hundred thousand training data.

A couple years later, Databricks published the results of comparing PySpark and Pandas: [Benchmarking Apache Spark on a Single Node Machine](https://databricks.com/blog/2018/05/03/benchmarking-apache-spark-on-a-single-node-machine.html). 
demonstrating that Spark can even be faster than single-node PyData tools because Spark can more easily utilize all cores due to its built-in parallelism. 
This study found Spark can also have lower memory consumption because it does not require loading the entire data set into memory.

## Use Spark to analyze a nontrivial data set
By nontrivial I mean something that takes more than a few seconds to process.  Using a challenging dataset can help make your project more credible. It makes the results more interesting, and gives you more to talk about.  The [Learning Apache Spark SQL](https://learn-apache-spark.thinkific.com/courses/spark-sql) course uses a 6.5 MiB dataset containing 1,095,695 words, 128,467 lines, and 41,762 distinct words. This size of dataset is just large enough to pose a challenge to a standard development grade laptop.

<p align="center">
<img id="img1" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/frequent_5-tuples.png" alt="Frequent 5 tuples" width="600px"
/>
<br>
<b>Figure 4. Most frequent 5 tuples in The Adventures of Sherlock Holmes </b>
</p>
Figure 4 shows the most frequent 5-tuples extracted from "The Project Gutenberg EBook of The Adventures of Sherlock Holmes by Sir Arthur Conan Doyle", obtained using [Spark SQL](https://learn-apache-spark.thinkific.com/courses/spark-sql) via a moving window function query.


## Compare Apache Spark using two different programming languages.

As PySpark's compilers continue to improve, the [difference between using python and scala continues to narrow](https://github.com/archivesunleashed/aut/files/1997998/udf_performance_doc.pdf). If you do everything using Spark SQL, then from there the [performance is equivalent](https://mindfulmachines.io/blog/2018/6/apache-spark-scala-vs-java-v-python-vs-r-vs-sql26). 
This comparison attracts keen interest as developers naturally 
attempt to reconcile the tension between ease of use and optimal performance.
Just be sure that your [implementation in each language is efficient](
https://stackoverflow.com/questions/32464122/spark-performance-for-scala-vs-python).


## Compare Spark to an alternative parallel computing platform
In this approach, you select a data set, and perform an analysis of it using two different cluster computing paradigms. 

This is a popular analysis because developers are always interested in comparing the performance of competing tools.  However, you better know each tool very well if you choose to explain this analysis in an interview setting 
because you need to understand each platform equally well. Here are some other ideas you can use to come up with your own comparative analysis.

* Apache Spark vs Flink
* Spark vs Hive
* Spark vs Map-Reduce
* Spark vs Storm
* Python Numpy or Pandas vs Spark on a single node.
* Python multiprocessing run on high-memory multi-cpu instance vs Spark on a cluster of commodity instances.


## Use Spark in conjunction with a cloud api 

Cloud apis provide powerful means of handling large datasets for certain applications; however, preparing the data for the cloud api may require substantial preprocessing. Cloud apis can also generate a lot of log data.  For example, I compared [IBM Watson and the Google Cloud speech-to-text cloud apis](https://pluteski.github.io/speech-to-text/on-batch-processing-audio-speech-to-text.html), 
and then compared the results by using sql to analyze the log data (cf., 
[on bleu scores and transcription rates](https://pluteski.github.io/speech-to-text/on-bleu-scores-and-transcription-rates.html), 
and [on transcription rate for noisy recordings](https://pluteski.github.io/speech-to-text/on-transcription-rate-for-noisy-recordings-ibm-ftw.html).  In this case, I used sqlite to run the queries. 
When I redo this I plan to use Spark SQL instead. 

This type of project gives you even more to talk about: how to integrate Spark with a cloud api, what operations are suitable for Spark and which ones are more suitable to do within the cloud api, what post-processing analytics steps are there for which Spark is especially suitable.  This demonstrates that you are not just expecting to run Spark in a sandbox isolated from other systems; you have some knowledge of how to use Spark to leverage other powerful computing frameworks. 

<p align="center">
<img hspace=10x src="https://github.com/pluteski/speech-to-text/blob/master/images/bleu_score_deciles.png?raw=true" alt="Bleu scores, IBM vs Google" width="600px"
</p>


## Use Spark to extract training features from a data set
Many data science jobs require the ability to train statistical models based on feature data gleaned from raw data. There is an abundance of data that you could use to demonstrate your ability to perform this. 

My [Apache Spark SQL course](https://learn-apache-spark.thinkific.com/courses/spark-sql) 
shows how to extract moving-window n-tuples from a text corpus. This would provide a good starting point for a feature extractor that vectorizes this into a form that can be provided as input to a neural network model. 
My [Apache Spark ML course](https://learn-apache-spark.thinkific.com/courses/sparkml-features) shows how to convert these n-tuples from arrays of strings to the sparse integer arrays used by Spark.ML's machine learning models.


<p align="center">
<img id="img1" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/moving_4tuples.png" alt="moving 4-tuples" width="550px"
/>
<br>
<b>Figure 5. moving 4-tuples </b>
<br>
</p>
Figure 5 shows moving 4-tuples extracted from the text corpus "The Project Gutenberg EBook of The Adventures of Sherlock Holmes by Sir Arthur Conan Doyle". Each row corresponds to a shifting ahead of the window one word 
relative to the previous row.


**Examples of modeling tasks**

* Statistically improbable phrases
* Anomaly detection 
* Topic modeling
* Recommender
* Trend analysis

**Examples of relevant models**

* Approximate K Nearest Neighbors
* Alternating Least Squares
* K-means clustering
* Streaming

If you can generate features for one of these types of models or tasks start-to-finish end-to-end, you are probably able to handle other modeling tasks.


# Demonstrating your knowledge of Spark internals
Being able to program the Spark computing framework is good.  
Being able to sensibly explain how it actually executed your code 
is better.  Being able to discuss how you would restructure the code 
or tune key parameters to improve the use of a critical compute resource 
is even better. Spark provides several means of generating visualizations 
that you can use to illustrate the compute resources used by 
your Spark code. 

## How to use the Spark UI to analyze performance
Once you've developed your Spark application and run it on a realistic dataset,
you'll want to demonstrate it in action. 
Even better if you can display your understanding of compute resources 
used by Spark when executing your code. 

The Spark UI is extremely useful for evaluating its usage of computing resources such as cpu, memory, i/o, and data transfer. 
This figure shows the Spark UI details for a sql query, 
showing the number of rows of data scanned, the number of files loaded, 
how much memory was used, and whether any data was spilled to disk from cache. 
Being able to analyze the internals of a system is an extremely practical 
skill that is desirable for most development positions, including data scientists. Being able to explain what this graph means and how it relates to your code would be an excellent way to convey your understanding of how your
code is executed by the system. 


<p align="center">
<b>Figure 6. Spark UI details for a sql query </b>
<br>
<img src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/L4.a.UI.SQL.query5.Plan1.png" alt="Spark UI DAG" width="800px"
/>
</p>
<br>
<br>

Figure 6 shows the resource consumption of a Spark query using the SQL tab within the Spark UI for a moving window query over 68 MiB of data, comprising 75,485 rows.
<br><br>

<p align="center">
<img id="img1" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/L4.a.UI.Sql.query5.Plan3.png" alt="Spark UI DAG" width="800px"
/>
<br>
<b>Figure 7. Query plans </b>
</p>
Figure 7 shows query plans used by the Spark query shown in Figure 6. 
This may suggest questions about the difference between different flavors of logical plan. It could be used to compare and contrast a logical plan and physical plan. 
<br><br>

<p align="center">
<img id="img1" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/L4.UI.DAG2.png" alt="Spark UI DAG" width="400px"
/>
<br>
<b>Figure 8. Detailed DAG Visualization </b>
</p>
Figure 8 shows a DAG visualization similar to the DAG visualization in the 
very first figure shown at the top of this article, but with additional detail enabled. Don't display this level of detail if you cannot back it up with 
answers to the questions it may trigger; but if you can pull that off you 
will be a more credible candidate. 
<br><br>

<p align="center">
<img id="img1" hspace=10x src="http://github.com/pluteski/speech-to-text/raw/master/blog/content/images/spark/L4.UI.TE1.png" alt="Spark UI DAG" width="800px"
/>
<br>
<b>Figure 9. Spark UI Executors tab </b>
</p>
Figure 9 shows the Executors tab in the Spark UI for an application that 
had completed 40327 tasks over the course of 3.3 hours on a single node cluster having eight cores. This evokes several questions, such as what does the number of tasks correspond to?  How do you suppose the compute resource consumption might have changed if running on a cluster instead of on a single node? It appears that 282 GB of data were inputted, but the amount of shuffle write was small.  What might explain this? 
<br><br>



<br>
# Summary
Having the competency required to win a desirable role is necessary but not sufficient. You also need to demonstrate your competency during the interview process.  This depends on communicating your understanding effectively. You can accomplish much of this in advance, by tackling a code project and publishing it. Writing up key results in a visually appealing way makes the 
presentation more compelling and puts your skills in a better light.

## To learn more
To see additional tips and project ideas, see my insanely low-priced online courseware on 
[Learning Apache Spark SQL](https://learn-apache-spark.thinkific.com/courses/spark-sql) and 
[Learning Apache Spark ML](https://learn-apache-spark.thinkific.com/courses/sparkml-features)


