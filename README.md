# Business Analytics & Information Economics

Dave Wentzel  
[LinkedIn Profile](https://linkedin.com/in/dwentzel)  
Office of the CTO, Microsoft  

## Abstract 

The value of data has become increasingly essential as a business asset for everyone.
 
Business leaders must creatively consider and implement unique ways to generate economic benefits from the expansive array of information assets available to them. As an emerging specialization, _infonomics_ can help executives make predictions about the behavior of markets and their customers.
 
We'll discuss methods for conceiving and generating transformative business benefits from available information assets, and how to use models from a data perspective to apply a variety of techniques for identifying new data driven value streams for your business. We'll also talk about what _data monetization_ really means and show you how to structure your data teams and projects so they have a better probability of succeeding.  

## Presentation

You can [download the presentation](./Infonomics.pdf) and follow along with me.


## Demos

>You can actually run the code yourself using either Synapse or vscode with the devcontainers extension.  When you open vscode and the folder where you cloned this repo it should ask you to re-open vscode using the devcontainer.  Once done, the code and data are ready for you to play with. 

1. **Prescriptive Analytics requires a simple analytics pattern**.  [`CETAS`](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-cetas) in Synapse works real well.  I have 2 versions of this demo.  Both do the same thing, one is simply a notebook where I can show better documentation and plots:  
    * [Demo SQL Script](./taxi-eda.sql):  import this to your Synapse workspace.  
    * [SQL Serverless Notebook](./taxi_eda.ipynb):  same business problem, similar code, different technology.  This uses Jupyter Notebooks...the standard for doing analytics in the data science community.  
2. **Avoiding Cognitive Mistakes**.  Prescriptive Analytics is primarily about answering the question _what do we do next?_.  This requires collaboration and critical thinking skills.  You don't want to make cognitive mistakes.  [Here's a case where we need to talk through the business problem so we tell management the RIGHT decision to make](./CognitiveMistakes.ipynb)
    * we use Synapse Spark for this example, you will need to import the notebook into your Synapse workspace
3. **Marketing Campaign Analytics**. Let's use some data and critical thinking to recommend _what should we do next?_ 
    * [Demo Notebook](./SocialMediaCampaignAnalytics.ipynb):  load this up into your Synapse workspace and execute.  
4. **Customer Behavioral Analytics**.  Let's look at who will purchase from us and why.  
    * [Demo Notebook](./Behavioral_Analytics.ipynb)


