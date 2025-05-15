# 📅 `Automate the Daily Excel Work to Prepare WIP Report` :  
> My objective here is to **completely Automate the manual Excel Work** to prepare the WIP(Work In Progress) Data and It's Status in **PPMC (Pre-Policy Medical Check-Up)** so that we can reduce the **45 Minutes of manual work to 3 Minutes** on daily basis for 25 Account Managers.


## 🔰 `Introduction` :
>**PPMC :** In the context of insurance, PPMC stands for Pre-Policy Medical Check-Up. This is a set of medical examinations and tests that a prospective policyholder must undergo before an insurance company approves their policy application. Here's a brief overview:

>**What is a Pre-Policy Medical Check-Up (PPMC) ?** <br>
A PPMC consists of various medical tests to assess the applicant's health status. These tests help the insurer determine the applicant's medical fitness and identify any pre-existing conditions. The results of these tests can influence the premium rates and coverage terms of the policy.

>**Importance of PPMC:** <br>
>1. Assessing Health Status: It provides a baseline health assessment for the policyholder.
>2. Identifying Pre-Existing Conditions: Helps insurers understand if there are any existing medical conditions that need to be considered.
>3. Determining Premiums: The results can affect the premium rates, ensuring they are appropriate for the individual's health status.
>4. Smooth Claim Settlement: The medical reports from the PPMC can be crucial during the claim settlement process.

>**Who Needs to Undergo PPMC ?** <br>
Typically, policyholders above a certain age (often 40 or 45 years) are required to undergo a PPMC. However, this can vary depending on the insurance company and the type of policy.


## 📊 `The Source Data` :
> Account manageers extract csv file from CRM in evening to prepare the WIP Report. This file have **185 Columns** and usually **lakhs of rows** based on their insurer volumes. They use the following columns to prepare the next day appointment tracker :
>- **CorporateName :** Insurer Name
>- **PatientName :** Name of Insured who will go under the medicals.
>- **ApplicationId :** Insured Application Number
>- **AppointmentStatus :** Current starus of Appointment
>- **LastCallStatus :** Final Call Status
>- **NumberofAttempts :** No of Call Attempts
>- **DND :** Particular Case has been marked DND (Do Not Disturb) or not.

# ⭐ `Let's start with the Program` :
>We will first build the logic and will explain and make the program. And after the we will make a function to repeat this daily task, make it simple for the account manager who is not well verse with python and save the time.
>1. In First Python Program we will build and explain the entire process
>2. In Second Python Program we will write the function to repeat this daily task, make it simple for the account manager who is not well verse with python and save the time.
