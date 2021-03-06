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
- [x] Day 34: Finished chapter 6. Logging and monitoring. I need to review the last 6 chapters tomorrow. 
- [x] Day 35: Started chapter 10. This chapter is about model interoperablity. Chapters 7-8-9 deal with the big 3 cloud providers. I want to get each of those chapters special time. 

Week 6: Deep Learning Begins: [Keras](https://drive.google.com/file/d/1yZlVKotI9AUgTydcrPrdhnz7yWAfk8_d/view)
---

- [x] Day 36: Finished Chapter 10. The chapter wrapped up with converting a few tf modles to onnx format. Then converting an onnx format to apple ML.
- [x] Day 37: Started Chapter 11. :) A bit less than half the chapter today. First section is about CLI tools. 
- [x] Day 38: Continued with Chapter 11. Encouraged new users to use highlevel 'severless' platforms as microservices. Don't invent the wheel, just use AWS coderunner. Sounds interesting!
- [x] Day 39: Finished Chapter 11. Thinking about re-reading chapter 12 though, I really need to start attacking all of the questions and exercises from the other chapters. 
- [x] Day 40: Skimmed back over Chapter 12 (Case study about Athlete Intel). Read some Appendix chapters: Tech certifications (lots of info on AWS, focused on Azure), Remote work, Think like a Venture Capitalist (when build an ML career). I guess I'm doing everything I can to avoid these exercises huh? LOL
- [x] Day 41: Finally reading chapter 8: Azure ML
- [x] Day 42: 2/3 of the way with chapter 8 - Registering Models, Registering Datasets and Deploying Models. 

Week 7: Deep Learning Continues: 
---

[Pytorch](https://github.com/fastai/fastbook)

[NLP with Pytorch](https://app.pluralsight.com/library/courses/natural-language-processing-pytorch/table-of-contents)

- [x] Day 43: Made changes to Rchamp also added a github actions test when merging into main. I want to add lints and tests to the package. Eventually I would like to set up some auto data collection into an s3 bucket. 
- [x] Day 44: Learned about xgboost4j in spark for distributed spark training. 
- [x] Day 45: Finished Chapter 8, Attempted to use sparkdl for XGboost on EMR. Failed! I'll try again tmr... I think
- [x] Day 46: Spent most of the day trying to get xgboost onto emr. Wether it be different EMR versions. My last attempt will try to build the xgboost4j library for spark. 
- [x] Day 47: Continued to try and build Xgboost4j for spark. Tried in EMR 5.19 and 5.33. 5.33 seemed to work but not 5.19! I don't think it will be woth the effort atm to continue down this path. 
- [x] Day 48: Read some more about MLOps in GCP. 
- [x] Day 49: Watched Ken Jee video about Business skills in data science.

Week 8: [TensorFlow](https://github.com/yanshengjia/ml-road/blob/master/resources/Hands%20On%20Machine%20Learning%20with%20Scikit%20Learn%20and%20TensorFlow.pdf)
---

- [x] Day 50: NOOOOOOOOOOO I missed this day :(
- [x] Day 51: Watched IAC with AWS CDK on [pragmatic labs](https://www.youtube.com/watch?v=-AWZAAjtH9o). Honestly, I need to revisit the plan for the rest of the challenge so that I can act on it. I've been ignoring the exercises :(. 
- [x] Day 52: Another day GONE! No time set aside for the challenge so I watched [GCP cloud functions for the impatient](https://www.youtube.com/watch?v=uyiF3MFFd7k)
- [x] Day 53: Added Chapter 2 exercises and questions to my private repo :) 
- [x] Day 54: Read some more about GCP in Chapter 9, started with GKE. Also watched this vedo on [DS for infrastructure](https://www.youtube.com/watch?v=LkZfqg3WYFg)
- [x] Day 55: Updated the CI for Rchamp package. Couldn't get it to completely work yet :(
- [x] Day 56: Watched part of [this screen cast](https://youtu.be/TBZKfyYWtXs)


Week 9: Advanced NLP with Python.
---

[spaCy for text processing](https://course.spacy.io/en/)

[LSTM and use cases](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

[NLP with Python](http://www.datascienceassn.org/sites/default/files/Natural%20Language%20Processing%20with%20Python.pdf)

---

- [x] Day 57: Watched some more of the DVC screen cast.
- [x] Day 58: NOOO9OOOO I FORGOT!
- [x] Day 59: Learned about DVC experiments. Looks a lot like AWS sage maker.
- [x] Day 60: NOOOOOOOOOOOO
- [x] Day 61: Watched [AWS lambda demo by Noah Gift](https://www.youtube.com/watch?v=-CqQ9SEcIOU). Pretty interesting! A tool I could use for when I build a twitch sentiment api call. Since AWS lambda scales...
- [x] Day 62: Watched an AWS study guide by Noah Gift. Going to be looking for an Azure study guide. Study guides for DS or MLE 
- [x] Day 63: [Intro CICI with DVS](https://www.youtube.com/watch?v=9BgIDqAzfuA). Feeling like im in a code rut :(.

Week 10: Advanced NLP with Python: Vector Models and RNNs. 
---

- [x] Day 64: Watch [#2](https://www.youtube.com/watch?v=kZKAuShWF0s) and [#3](https://www.youtube.com/watch?v=xPncjKH6SPk) of the MLOps playlist from DVC
- [x] Day 65: Read about NLP word embeddings used in non-NLP settings. Such as product similarty for online purchases. **[Blog HERE](https://towardsdatascience.com/embeddings-with-word2vec-in-non-nlp-contexts-details-e879b093d34d)**
- [x] Day 66: Watched [#4](https://www.youtube.com/watch?v=rVq-SCNyxVc) of MLOPs playlist. This is using custom code-runers for CI/CD which I think is cool. This is good for using GPU runners for deep learning workloads. 
- [] Day 67
- [] Day 68
- [] Day 69
- [] Day 70
