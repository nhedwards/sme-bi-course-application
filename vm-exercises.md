# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## Exercise 1: Things just got personal

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

Create a personalized view of a visualization.

#### Context

You had an interesting conversation with one of the customer service managers that sparked an idea: segmentation. By segmenting customers based on demographic data, you may be able to drive more insight into reasons why churn is higher for different age groups. The Customer Service Team gave you their Churn report, but it doesn't have quite what you're looking for. Perhaps there's more data than meets the eye? With the _Personalize_ feature, you may be able to make use of this report after all.

#### Steps to be executed by the student (max 6)

1. Open the `ex-1-initial.pbix` report from the `Exercises` folder.
2. Open up the _Personalize_ pane for the **Churn by category** visualization on the **Groups and Categories** page.
3. Change the _Pie chart_ to a _Stacked column chart_.
4. Add `Senior` to the _Small multiples_.

#### Exercise question:
Which of these statements is **FALSE** of the churn category based on this analysis?

1. **Seniors were more concerned with price than non-seniors.**
2. There is no significant difference in the churn category between seniors and non-seniors.
3. Competitors were the top churn categories in both cohorts.

#### Success message:
Nice work! There doesn't seem to be a big different in churn categories between seniors and non-seniors. This is still valuable information, as it means we should focus on solving the same issue for all customers.

#### End goal:

![Screenshot 2024-01-28 at 3 28 22 PM](https://github.com/nhedwards/sme-bi-course-application/assets/107631815/b0e65e10-ae53-4803-b2a8-5fde954a7070)

## Exercise 2: Bookworm

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

Create Personal Bookmarks, change them, and navigate through the _Bookmarks_ pane.
#### Context

When personalizing reports, Bookmarks save the state of the report at the moment you create them. Creating _Personal Bookmarks_ is a pro-move that will save you tons of time because instead of having to redo personalized views over and over again, you can simply save the bookmark and return to it whenever you want.

_Continue using the same pbix file._

#### Steps to be executed by the student (max 6)

1. Create a _Personal Bookmark_ of the report in its current state and name it "Churn by Senior Cohort".
2. Edit the **Churn Rate by Contract Category and Gender** visualization to split the categories by `Senior` instead of `Gender`. (HINT: Add `Senior` to the _Legend_.)
3. Update the _Churn by Senior Cohort_ bookmark to reflect the current state of the workbook.
4. Open up the _Bookmarks_ pane. (HINT: Click on the Bookmark icon, then _Show more bookmarks_.

#### Exercise question:
Which of the following bookmarks are available in this report? Select all that apply.

- [x] Churn by Senior Cohort
- [ ] Default
- [x] Bookmark 1
- [ ] Iason is Spiderman

#### Success message
Awesome work! The bookmarks you create will show up in your Personal bookmarks section, and Report bookmarks are the ones created by the report publisher. Using bookmarks, like reading a book, makes it easier to find your spot when you come back to your report.

#### End goal:

![Screenshot 2024-01-28 at 3 42 29 PM](https://github.com/nhedwards/sme-bi-course-application/assets/107631815/b2b04c3f-3fce-47cd-b888-bea1d7727e90)
