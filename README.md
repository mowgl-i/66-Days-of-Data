**Days of Data part 2** 
---

Week 1: Revisit previous work in python. Build python reflex.
---

Using [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook).

---
- [x] Day 1: Finished [Tina's](https://www.youtube.com/channel/UC2UXDak6o7rBm23k3Vv5dww) [SQL for Tech and Data Science Interviews](https://www.udemy.com/course/sql-for-tech-and-data-science-interviews/learn/lecture/26613654#questions/15758816)
- [x] Day 2: Spinned up a GCP Virtual Machine and loaded it with Python, Visual Studio and some additional helpers (Juypter, Black). First time coding in VS, liking it so far. Hopefully this VM set up will jumpstart some coding assignments untill I get some official credentials to work with client data. Test 
- [x] Day 3: Revisited Chapter 3 of Linked book above for pandas. Read and Looked at Pandas Profiling. May actually use in the next week. 
- [x] Day 4: Off topic - Looked at a few different ML certs. My productions skills are lacking, so I may need to change the content of this 66 days to better align with my weaknesses. Also re-built the VM to Linux and learned about Poetry(Dependency Manager)
- [x] Day 5: Yesterday and today were short on time. At work I learned how to use pyenv and poetry for version and dependency management. My goal is to remote into the GCP Virtual Machine (where pyenv is installed), and spin up two projects each with different versions of python, and different versions of the desired libraries. Pretty neat stuff!
- [x] Day 6: Briefly learned about Docker, Kubernetes and Kubeflow for machine learning. I have alot more to learn about containerized environments for ML deployment. 
- [x] Day 7: Learned about classes and Self. Now gotta learn to to make ML classes 😭. Also forgot to push this, this it posted day 8 😅 rip contributor streak.


Week 2: Looking for indepth pandas magic to speed up analysis. **I actually need to update the rest of the challenge since my objectives have changed a bit.** 
---

[Welcome to advanced pandas](https://www.kaggle.com/residentmario/welcome-to-advanced-pandas)

[Advanced pandas article](https://towardsdatascience.com/learn-advanced-features-for-pythons-main-data-analysis-library-in-20-minutes-d0eedd90d086)

[From novice to advanced pandas](https://towardsdatascience.com/30-examples-to-get-you-from-a-novice-to-an-advanced-pandas-user-e6eb4e8750b7)

[Pandas to optimize speed and memory](https://medium.com/bigdatarepublic/advanced-pandas-optimize-speed-and-memory-a654b53be6c2)

[Advanced pandas features](https://www.kdnuggets.com/2019/10/5-advanced-features-pandas.html)

[Pandas Cheat Sheet](https://www.educative.io/blog/pandas-cheat-sheet)

---

- [x] Day 8: Read about the google style guide. Learned more about asserts and how to handle Try and Except blocks. I must get better at Docstrings as well for documenting classes. Also didn't know you can use Self outside of classes. 
- [x] Day 9: Brought code up to google docstring style. Used type hinting in a function. Learned briefly about to create python packages.  
- [x] Day 10: Writting an Python package complete with own modules. Nothing special just conducting RF model on the Iris dataset. Having it take key arguments, lots of self.thing. It feels much more modular this way. 
- [x] Day 11: Somewhat finished the package. It has it's own modules and .py files, runs main() when invoked and takes command line arguments with docopt. Also breezed through this: [Applied Pandas - Twitter Analytics](https://store.metasnake.com/courses/applied-pandas-twitter-analytics). I picked up this course from humble bundle. Going to read Noah Gift's ['Cloud Computing for Data Analysis'](https://leanpub.com/cloud4data). Hope to keep up with this for a few days on this challenge. 10 chapters, 1 chapter a day?? He also JUST published [Practical MLOps](https://github.com/noahgift)
- [x] Day 12: Read the first chapter of 'Cloud Computing for Data Analysis'. YO! That chapter was jammed packed with resources. I read through it, and tmr I will go through the linked resources. Then read Chapter 2 on day 13, then go over chapter 2 resources on Day 14? 
- [x] Day 13: Set up Azure resourse, Azure ML, Azure KeyVault, Azure Storage, Azure Insights... Just gotta get some data in there next. Hope to read chapter 2 tmr. 
- [x] Day 14: Light day today. Watched a brief video about [comparing different implementations of gradient bosting algos](https://www.youtube.com/watch?v=yO6gJM_t1Bw). Of course aglos should be considered carefully when implementing but CatBoost came out on top for accuracy and speed(top speed meaning slowest algo). 

Week 3: Learn about machine learning in the cloud -> AZURE
---

[Intro to ML with Python](http://noracook.io/Books/Python/introductiontomachinelearningwithpython.pdf)

['Cloud Computing for Data Analysis'](https://leanpub.com/cloud4data)

[Perform data science with Azure Databricks](https://docs.microsoft.com/en-us/learn/paths/perform-data-science-azure-databricks/)

---

- [x] Day 15: Re-formatted my google sheet where I track my stock trading. 
- [x] Day 16: Learned about Databricks and Azure. Having trouble uploading data to the blob. Delta lakes are cool. I gotta think harder about mounting to the blob/container and working with the data. 
- [x] Day 17: Completed a intro to databricks and azure notebook. Attached parquet file to my very own file storage and mounted it to the notebook!
- [x] Day 18: Read chapter 2 and began chapter 3 of ['Cloud Computing for Data Analysis'](https://leanpub.com/cloud4data). Topics where cloud computing foundations and then Docker, Kubernetes, Hybrids clouds and some more! This book is so insightful and has neat little links which lend themselfs to a great mobile reading experience. 
- [x] Day 19: Through the week I was working on this course - ['Perform data science with Azure Databricks'](https://docs.microsoft.com/en-us/learn/paths/perform-data-science-azure-databricks/). I finished that today. Hopefully soon I can put it to use. I have an idea of automating my reddit classifer or 'upserting' data from my IoT device into a vizualization. 
- [x] Day 20: Watched [How Starbucks Forescasts Demand at Scale wiht FaceBook Prophet and Azure Databricks](https://vimeo.com/391153676/d1d8c31c1c). At first I didn't see the value of building a single product-price model but the power came from using pandas UDFs to train models on each product-store combo which you can distribute the workload on Azure Databricks with Spark. B) Also updated Next weeks goals. 
- [x] Day 21: Attended satRdays - an R conference. I listened to three talks.

1: Intro to CatBoost
2: The Current State of NLP and Text-Based Machine Learning Modeling. 
3: Survey, Linguistics, Analysis kNowledge Guide: SLANG, a tool for multi-faceted text analysis in R.

Week 4: Practicle MLOps: by Noah Gift. 
---

I need to ramp up my cloud skills, and try to become as 'full-stack' as possible. Not sure how far this book will take me into 'full-stack' but it's a start!

[Practical MLOps: Operationalizing Machine Learning Models](https://www.oreilly.com/library/view/practical-mlops/9781098103002/)

---

- [x] Day 22: Read Chapter 4 and 5 of ['Cloud Computing for Data Analysis'](https://leanpub.com/cloud4data). Topics where Cloud Storage (AWS mainily) and challenges with distributed computing (the issues with CPU computing and benifits to GPU and TPU).
- [x] Day 23: Read the prologue and 1/2 of Chapter 1 -> [Practical MLOps: Operationalizing Machine Learning Models](https://www.oreilly.com/library/view/practical-mlops/9781098103002/) Topics where: What is MLOps? How did MLOps become needed? The fundamentals of MLOps. The intersection of ML and DevOps = MLOps. Kaizen, continuous improvement.
- [x] Day 24: Finished chapter 1: Continues to address the usefulness and need for MLOps. Some exercises and questions are prompted which I plan to answer tomorow. Began reading Chapter 12 (1/2). This chapter is about case studies and linking MLOps to the real world. I thought this would be a good place to start so that the excercises would be more engaging. Reading these case studies is building my motivation to begin MLOps. I will think about my previous work and see if I can save it using MLOps. 
- [x] Day 25: Built a twitch chat websocket on python. Trying to connect it to AWS Kinesis for streaming data analysis. I plan to read MLOps tonight before bed. 
- [x] Day 26: Finished chapter 12 - began Chapter 2. Also connected the python script to Kinesis firehouse! Though, I can't see the raw data, I can see the transactions.
- [x] Day 27: Read a little bit more of Chapter 2. Completed a few exercises from Chapter 1 (CI and CD with Github actions and AWS Codebuild!). Build makefiles and tests to facilitate the continuous integration. Also finished the Factfullness audio book. 
- [x] Day 28: Finished Chapter 2! Short day today. 


Week 5: Cloud data products and their relevance to my work. A goal in mind here is to send twitch data into a Bigquery DB or AWS Bucket. 
---

[Understanding Cloud data services](https://www.kdnuggets.com/2019/06/understanding-cloud-data-services.html#:~:text=Cloud%20Vendors%20examples%20include%20AWS,Data%20processing%20and%20analytics%20workloads.)

[Ai with Google](https://ai.google/education/)

[Accenture Applied AI](https://www.accenture.com/us-en/services/applied-intelligence/solutions-ai)

---

- [x] Day 29: Read Half of Chapter 3! It was about container and contained a walkthrough of setting one up (I did follow it....YET)
- [x] Day 30: Finished Chapter 3. The last half was about edge computing and highlighed where containers may play a role in configuring ML models for edge deployment. I'm beginning to understand how useful containers can be. Also messed around in Gitlab. Hoping to do some CI/CD in Gitlab tomorrow.   
- [x] Day 31: Read Half of Chapter 4. I'm sensing a pattern here! I believe 1/2 chapter (about 20 pages) seems to fill me up on the reading. Got the CI/CD working in gitlab today :)
- [x] Day 32: Finished Chapter 4. Added a basic RF model into the MLOps repo complete with lints and tests so that the repo builds correctly with every push :)
- [x] Day 33: Finished Chapter 5. This chapter was about AutoML. I was today years old when I found out apple has an autoML solution built-in. 
- [] Day 34
- [] Day 35

Week 6: Deep Learning Begins: [Keras](https://drive.google.com/file/d/1yZlVKotI9AUgTydcrPrdhnz7yWAfk8_d/view)
---

- [] Day 36
- [] Day 37
- [] Day 38
- [] Day 39
- [] Day 40
- [] Day 41
- [] Day 42

Week 7: Deep Learning Continues: 
---

[Pytorch](https://github.com/fastai/fastbook)

[NLP with Pytorch](https://app.pluralsight.com/library/courses/natural-language-processing-pytorch/table-of-contents)

- [] Day 43
- [] Day 44
- [] Day 45
- [] Day 46
- [] Day 47
- [] Day 48
- [] Day 49

Week 8: [TensorFlow](https://github.com/yanshengjia/ml-road/blob/master/resources/Hands%20On%20Machine%20Learning%20with%20Scikit%20Learn%20and%20TensorFlow.pdf)
---

- [] Day 50
- [] Day 51
- [] Day 52
- [] Day 53
- [] Day 54
- [] Day 55
- [] Day 56


Week 9: Advanced NLP with Python.
---

[spaCy for text processing](https://course.spacy.io/en/)

[LSTM and use cases](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

[NLP with Python](http://www.datascienceassn.org/sites/default/files/Natural%20Language%20Processing%20with%20Python.pdf)

---

- [] Day 57
- [] Day 58
- [] Day 59
- [] Day 60
- [] Day 61
- [] Day 62
- [] Day 63

Week 10: Advanced NLP with Python: Vector Models and RNNs. 
---

- [] Day 64
- [] Day 65
- [] Day 66
- [] Day 67
- [] Day 68
- [] Day 69
- [] Day 70
