# USA West Analytics Machine Learning Competition

Adventure Works Cycles, a successful (albeit fictitious) bicycle manufacturer has tasked your team with analyzing their sales data to learn more about their customers. Foremost, they are looking for insights on why their customers choose to purchase their products.

## What you’ll predict (links to database reference)
Build a model to predict the [Sales Reason](http://www.elsasoft.com/samples/sqlserver_adventureworks/SqlServer.SPRING.KATMAI.AdventureWorks/table_SalesSalesReason.htm) for every [Sales Order](http://www.elsasoft.com/samples/sqlserver_adventureworks/SqlServer.SPRING.KATMAI.AdventureWorks/table_SalesSalesOrderHeader.htm). The [entire dataset](http://www.elsasoft.com/samples/sqlserver_adventureworks/SqlServer.SPRING.KATMAI.AdventureWorks/default.htm) is available to you to – understanding the relationships in the data is key.

## Competition data
The only data available for this competition is available here. We’ve taken a random sample of orders from the original dataset and have made ~25k sales orders available to you. Although the rest of the set is publicly available, **the use of the omitted orders is strictly prohibited**. 

## Timeline and deliverables
- The dataset will be made available on October 3rd
- Teams will provide a weekly check-in on the Teams channel to discourage last-minute cramming before the deadline. Be sure to cover:
  - What was worked on last week?
  - Who worked on what?
  - Blockers/concerns?
- Submission will close at 11:59 PM on November 5th. No changes will be accepted after this time
- Teams’ presentations begin November 9th. Each team will present to the TC over the course of the following weeks, book your spot early!
  - 10-15 minute presentation
  
## Judging
**Accuracy**
- Models will be fit against a test data set and a confusion matrix will be used to evaluate the model’s accuracy. Judges will consider both precision and recall within the evaluation.

**Data engineering**
- A model is only as good as the data its trained on. Judges will examine how well you prepared and cleaned your data.
- Feature engineering is the art in the science. How creative can you get and how do new features improve your model?

**Interpretability**
- How well can others interpret your model, code and approach to problem solving?

**Prize**
- The winning team receive 4000 Go Team Points per member.

## Due date
Submission closes November 5th at 11:59 PM

## Other considerations
- There are roughly 25k unique sales orders available for your training and testing sets, make sure you use this data is appropriately split!
- This data is unlabeled, so you’ll need to reference the database description available [here](http://www.elsasoft.com/samples/sqlserver_adventureworks/SqlServer.SPRING.KATMAI.AdventureWorks/default.htm). As with real-world ML problems, dealing with data is most of the work
- You may enter as an individual or team. Groups are strictly limited to a max of 3 members **(teams with 3+ will be disqualified)**
- Please share you questions or concerns on the Teams channel. A brown bag workshop session will be held on Oct 19th to assist anyone with outstanding questions.
- Billing code – you may bill up to 4 hours your training code
- Any further questions – contact matt.russell@avanade.com
