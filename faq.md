---
title: FAQ
---

Please see our <strong>rough</strong> roadmap before reading other questions.   

![Roadmap](/images/public_roadmap.png)


# Frontend UI

### I see blank screen as soon as I login. Where is my content ?
All the reports are available under Dashboads menu. Please click "Dashboards" from the top menu and you will see the reports

### Can I select multiple values in filters e.g. multiple employers, multiple states, multiple cities, multiple job titles etc.
Multiple values are available only in *paid subscriptions* for B2B users. For B2C users, we are working on a new subscription to enable multiple input-values for filters. Multiple values increase the load on our big data servers exponentially, so at this point the feature is not available for free tier  
<br>
<br>

### Can I get an email copy of the report ?
We do not provide email reports at this point, because data is changing frequently and we cannot trigger an email for every data change to thousands of users. That said, this is a feature that is actively being worked on. Please see our Roadmap for further information

### I forgot my password
We are actively working on providing a forgot password on login page. However at this time, we are tackling multiple priorities, so if you forgot and every other option is in vain, please write to us directly at [email](mailto:hello@symmetrics.fyi).  
<strong>Note</strong> We will try our best to respond as quickly as possible  
<br>
<br>
<br>

# DATA 

### Which goegraphic regions do you cover ?
Symmetrics covers USA and all its 51 states (all cities, postal codes, metro areas, DMAs underneath) data. We are working with our partners across the globe for countries like India, Canada, Australia, UK and other countries and will release the data once it passes through our quality checks and legal team. 
<br>
<br>

### Which years do you cover ?
We cover data from years 2001 - current   
<br>
<br>

### What industries do you cover ?
We cover ALL industries. There are at least 3000+ industries under which all companies are classified. Examples of highest paid and highest employed are “Custom Computer Programming Services”, “Computer Systems Design Services”, “Engineering Services”, “General Medical and Surgical Hospitals”, “Investment Banking and Securities Dealing” and so on.

We also cover industries that hire medium-skilled workers too like Agricultural, Medical (nurses etc.), Hospitality and Tourism (Cruise Ships) etc. 

<strong>Note:</strong> We do not have data yet on the portal displayed for medium-skilled workers, but we are in the final stages of our development and it will be made public very soon  
<br>
<br>

### What job families / types do you cover ?
We cover ALL job types. There are close to 1500+ job families and types, that every job title falls under. Examples of highest paid job types/families are “Chief Executives”, “General and Operations Managers”, “Computer and Information Systems Managers”, “Financial Managers” and so on.  
<br>
<br>

### How accurate is the data / Why should I trust your data ?
Our data is from the horse’s mouth i.e. public disclosure information released by USCIS/DHS under FOIA act. Our insights are powered by <strong>~10million</strong> de-duped (non duplicates) data points and by far the <i>only portal on the internet</i> that crunches so many data points. For statisticians out there, all our competitors provide sample data and at best dump tables and expect readers to figure out insights. We took extra care to clean up the data, make meaningful inferences (interpolation and extrapolation) using data warehouse, database, and data science inferences and best practices in the big data domain. We <strong>tested the accuracy of data</strong> after building it and ensured it meets our quality standards, before releasing it to the world. If you have further questions on data accuracy, do not hesitate to reach out to us. We will try and respond depending on the availability of support staff, but responses are not guaranteed.

Below are some of our high level strengths that none of the competitors achieved till date

![Symmetrics vs. Competitors](/images/symmetrics_vs_competitors.png)  
<br>
<br>

### How can I trust Smmetrics as a B2B user (my clients will ask me the same question and I need to be in a position to defend)
If you are subscribed to us as B2B, our initial presentations will highlight on the logic, algorithms and practices used to build the platform. Recruiters, Staffers and b2b domain experts in the HR/Recruitment/B2B domains can instantly recognize if the metrics they see on our platform reflect truth or not. If you have strong evidence that a particular metric (for an employer, job title, state,city etc.) is not so correct, please reach out to us with clear evidence. Further, we would ask that you check with your technical architects, data architects , data engineers and application teams BEFORE reaching out to us on the accuracy of data. Lastly, you can always contact us  
<br>
<br>
# Do you sell my personal information?
We take <strong>PII (personally identifiable information)</strong> data very seriously and DO NOT sell information to any third parties.  
<br>
<br>

### Why are all years, states, cities, companies not showing up in the filters ?
The data comprising of all years, states, cities, postal codes, companies (or employers) is a very large number. For free subscriptions, we cannot necessarily show all values, because that increases load on our servers and might cause resource contention to other paid users. Further, for sustenance and to be able to support our growing staff, we would need a bit more care (aka. convert to paying subscription) from your end if you value such a platform.   
<br>
<br>

# Subscription

### What are your subscription plans ?
We have two types - <a href="/symmetrics_pricing" target="_blank"><strong>B2C and B2B.</strong></a>

For B2C - there is a) Free plan that gives you enough information to get a flavor of the top n cities, states, employers, job titles etc. b) <a href="https://forms.gle/C6WkCRHP9CRfcX7j9" target="_blank"><strong>paid subscription plan</strong></a> that will expand your data search and reports data

For B2B - We are in Beta phase and any B2B customer at this point needs to reach out to us directly through <a href="https://forms.gle/fyPUSry73E7bSZ1c6" target="_blank"><strong>the form.</strong></a> One of our staff members/Sales Team will reach out to you for further conversations. In general, as a guidance we give B2B customers granular access to data (For e.g. depending on your GEO area that you operate in, we provide access to the data covering the state of California, all cities under it, all employers and corresponding job titles with a monthly and yearly subscription fee per user)  
<br>
<br>

### Even with paid subscription, I am unable to select the specific employer/job title in the filters (that I am looking for) in either what-if or goal based reports
The paid subscription (for all users) allows seeing top 1000 values in the filters drop down. For e.g. if there are 50,000 employers for State ‘CA’ in year ‘2021’, displaying all 50k employers is not a great idea for the web experience, server load and the cost to provide a platform at scale. After working with 100s of thousands of candidates and recruiters/employers, we realized that all searches are done under 1000 and our clients get what they need.

That said, for B2B clients (recruiters and employers), we can provide your specific employer information as a special case for an additional fee structure or complementary depending on the contract we have with you.

For B2C clients, if you are looking for a specific company/employer and details , please reach out by filling in the details on the google form and we will get back to you  
<br>
<br>

### Can I unsubscribe and ask my user be deleted ?
Absolutely ! We respect your privacy and that is one of our core values. Write to us providing your full details, so that we know it is exactly you asking the user to be deleted at [email](mailto:hello@symmetrics.fyi)


# General

### Why did you choose .fyi ?
There is no specific reason , but we thought the suffix aligned with the information that we provided and also reflected `how` we provided the information without being intrusive (FYI = For your information) 

### I am a B2B subscriber, can I get my own tenant ?
We would need to understand your definition of tenant before we can help you. Below are few concerns that might be relevant to tenancy  
- Tenancy for data 
- Tenancy at meta data 
- Infrastructure tenancy and so on...  

You can compare tenancy to hosting in the CMS hosting space. Hosting providers give options for shared hosting or dedicated hosting depending on agreements. We can provide the same. Please reach out
