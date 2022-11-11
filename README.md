# Data_Analysis_Case_Study
This repo hosts a case study that you can use to tests your data analysis skills. 
Navigate to the datasets folder of this repository and find the dataset for this task (mobile_money_data.csv).

# The Task
A certain company has recently finished the data collection for a project on the use of Mobile Money services and the experiences of Mobile Money customers in three districts of Kenya.

The dataset has been provided and you have been asked to write a short summary outlining key initial findings to be discussed by the Specialist Advisory Board for the study. Members of this Board include representatives from the National Bank of the country, the Utilities Regulatory Authority and NGO’s focusing on access to digital financial services and associated consumer protection issues.

These key initial findings will be used to inform the next stage of the study which includes focus group discussions with mobile money customers. Correctly identifying and interpreting issues that negatively affect mobile money customers is very important for prioritizing topics to take forward in the qualitative research.

You are responsible for performing all the statistical analysis required and writing up the key findings. You should remember that the target audience do not have a statistical background. To analyse the dataset please use Stata, R or Python. You may also consult any resources you like, except other people.

The research manager wants you to address the following points in the key findings document and working files:

1. During the survey, participants listed all the different types of financial account that they have registered. The resulting data has a format where there is one observation per account type. Format the data so that there is now one observation per participant. (5 marks)

2. Create two dummy variables for whether each participant is: i) financially excluded and ii) digitally financially included. What are the overall rates of financial exclusion and digital financial inclusion for the combined population of these three districts? (10 marks)

    a. Financial exclusion is defined as not having registered for any type of financial account including accounts with: Mobile money operators, banks, micro-finance institutions (MFI’s), savings and credit cooperative organisations (SACCO’s) and village savings and loan associations (VSLA’s).

    b. Digital financial inclusion is defined as having at least one registered account with a mobile money operator or an online bank account.

3. Describe in a few short paragraphs how the mobile money market is divided between the three companies. Include at least one chart or table to illustrate your findings. (15 marks)

4. Is there a difference in the share of customers who have experienced failed mobile money transactions in rural and urban villages? If so, is it statistically significant? Explain your findings including any assumptions and limitations. (15 marks)

5. What variables are good predictors that someone will cancel their mobile money account? Discuss what causes a customer to stop using their mobile money account including how strong the evidence is. (20 marks)

Additional marks will be given for:

* The client readiness of your written document (5 marks)
* The quality of your code (5 marks)

TOTAL: 75 marks


# Variable Description

hhid - Household ID

weight - Sampling Weight

account_num - Account Number

account_type - Type of account

district - District of household

urban - Household location in urban or rural village

gender - Gender

age -Age

hh_members - Number of household members

highest_grade_completed - Highest grade completed

mm_account_cancelled - Has cancelled a mobile money account in the past

prefer_cash - Preference for cash over cashless payment methods

mm_trust - Do you trust mobile money?

mm_account_telco - Please select the providers for which you have a mobile money account

mm_account_telco_main - Which would you consider your main Mobile Money account?

v234 - I understood the terms and conditions when I registered for a mobile money account.

agent_trust - Do you trust mobile money agents?

v236 - Have you ever taken a mobile money loan?

v237 - Have you ever had issues with the network being unavailable for mobile money transactions?

v238 - Before making a transaction are you clear about the fees?

v240 - Has a transaction ever failed to go through?

v241 - Has an agent you’ve dealt with ever not had enough cash or efloat available?

v242 - Do you have a copy of the mobile money terms and conditions?

v243 - Do you understand how and where to complain if you have an issue with mobile money?

v244 - Have you had an issue successfully resolved after making a complaint?

v245 - Do you understand what data mobile money providers collect about you?

v246 - Have you been a victim of fraud?
