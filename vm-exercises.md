# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Learners will be able to learn correlation and windows correlation function using tableau

#### Context

Windows functions are useful inbuilt functions in tableau that provide efficiency and are used for comparitive analysis. Combining them to correlation matrices add more insights and better consistency to the data visualization. They help in deriving correlation amongst random variables and their real life applications involve weather forecasting, research and analysis, engineering, etc.

#### Steps to be executed by the student (max 6)

*Below are the steps to be executed by learners*

- Drag and drop start date to rows shelf and measures names to columns shelf
- Drill down the end date and add mesures names to filter section, filtering out budget and expense (the two measures to be used)
- Drag and drop measure values to text under marks section and Write down the two calculated fields, one for correlation and the other for windows correlation as shown   in the screencast/video.
- Add these two calculated fields to the view by adjusting measure names in the filter section and observe the difference between them.

#### Exercise question:

Which of the following is true about WINDOWS function?
•	WINDOWS function require aggregated values
•	WINDOWS function does not require aggregated values
•	WINDOWS functions utlize aggregated values by default
•	WINDOWS functions don't use over clause


#### End goal:


![Final_Vizualization_Correlation](https://user-images.githubusercontent.com/122206001/211250618-3ae6b095-914f-4c69-b9f2-f672d5497972.png)




## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

Learners will be able to learn covariance and windows covariance function using tableau

#### Context

Windows functions are helpful, efficient, built-in Tableau features that are utilised for comparative analysis. The data visualisation gains more insights and improves consistency when they are combined with covariance functions. They aid in determining the degree to which two random variables are dependent on one another, and their real-world applications include forecasting the weather, studying the human body and life sciences, finding new drugs, etc.

#### Steps to be executed by the student (max 6)

Below are the steps to be executed by learners

- Select two measures, namely budget and expense and Write down the two calculated fields, one for covariance and the other for windows correlation as shown   in the     screencast/video (you can choose different start and end time intervals for your visualization).
- Drag and drop location to detail and priority to color under marks section.
- Drag and drop trend lines and average lines from analytics pane (you can choose trend line to be linesr, logarithmic, etc as per your choice).
- You can now observe the performnace according to location and priority of projects.

#### Exercise question:
 Which of the following is true about WINDOWS function?
•	WINDOWS function does not require to add a start date and end date
•	WINDOWS funnction require adding a start and end date

#### End goal:

![Final_Visualization_Covariance](https://user-images.githubusercontent.com/122206001/211244313-f22955e8-2d0d-44dd-9f7e-6cbe691ab844.png)


