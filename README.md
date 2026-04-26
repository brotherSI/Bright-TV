# Bright-TV Case Study
## Overview
BrightTV is a subscription-based streaming service seeking to grow its subscriber base during the current financial year. The company's CEO has identified subscriber growth as the primary strategic objective
and has engaged a data analyst to provide actionable insights that will support the Customer Value Management (CVM) team in achieving this goal.
## Objective
The aim of the analysis is to answer key business questions:
| Business question | Description |
|------|-------------|
| What are key user and viewship trends? | Examines how subscriber numbers and viewing behaviour evolve over time, including growth patterns, peak usage periods, and shifts in audience engagement across the platform. |
| Which factors influence content consumption? | Identifies the key drivers such as genre, device, time of day, or user demographics that determine what content subscribers watch and how much they consume. |
| What content strategies can increase engagement on low-activity days? | Explores targeted programming, promotions, or scheduling tactics that can boost viewership during typically quiet periods like weekdays or off-peak seasons.|
| What initiative can drive user growth and retention? | Looks at acquisition and churn-reduction strategies such as referral programs, personalisation, or pricing models that attract new subscribers and keep existing ones engaged. |

## How the Case Study was Executed

### 1. Data Ingestion & Setup
* Load raw excel file dataset into Databricks environment
* Perform a left join function to combine tables: Uder Profile table and Viewership table

### 2. Data Cleaning & Quality Checks
* Performed null handling (replacing "None" values with meaningful substitutes)
* Removed adn validated duplicated session records
* Standardized categorical fields (Channel, Province, Race)
* Converted timestamps from UTC to South African time (GMT+2)
* Cleaned and transformed sessionduration into numeric format

### 3. Featuring Engineering

#### 3.1 Time-Based Features
* Day of the week, Month
* Time buckets (Morning, Afternoon, Evening, Night)
* Weekday vs Weekend classification
* Month pattern (Beginning, Mid, End)

#### 3.2 User & Behavioural Features
* Active days per user
* Session frequency
* Viewer segmentation (Light -> Super viewrs)

#### 3.3 Business Metrics
* Total Watch Time (hours)
* Average Session Duration
* Session per User
* Daily Active User (DAU) & Monthly Active User (MAU)
* Retention Rate
* Stickiness Ratio (DAU/MAU)
* Churn Indicator
* Growth Rate

### 4. Exploratory Data Analysis (EDA)

#### 4.1 Used SQL to analyze:
* User engagement trends over time (daily, weekly, monthly)
* Content consumption by channel
* Viewing behaviour across time bucket
* Demographic analysis (Age, Gender, Province)
* Rention and churn patterns
* User activity distribution and engagement levels

### 5. Data Visualization & Reporting 

#### Tools used:
* Power BI
* Microsoft Excel (Pivot Tables & Charts)
* GoogleLooker Studio
* Loveable:

#### Visualized:
* User growth trends (DAU, MAU)
* Engagement pattern by time of the day
* Channel performance
* Retention and churn metrics
* Demographic distribution
* Viewer segmentation (watch categories)


## Insights I have Found
**1. Location**

Certain areas, such as Gauteng, might experience considerably greater viewership than other regions, largely due to factors
like population concentration and internet availability.

**2. Live Event (Sport and Other Major Events)**

Significant sporting occasions,including historical ones have the potential to attract a large number of viewers.
Broadcasting events in real time or replaying memorable games can also bring in an audience

**3. Age Group and Audience**

Demographics Different age groups tend to have distinct viewing habits, with younger viewers gravitating towards high energy genres such as action, whereas older audiences tend to lean towards drama content. 

**4. Product (Content)**

The variety, standard, and uniqueness of Bright TV programming are key elements that influence how many people tune in.
Highlighting genres that are currently popular and in demand can lead to a notable increase in viewership.

## Tools Used for the Case Study

* SQL
* Databricks
* Power BI & Google Looker Studio
* Microsoft Excel
* Canva (Presentation)
* Miro (Planning)

## Summary 
Viewership on Bright TV is shaped by four core factors. Geographically, regions like Gauteng naturally attract higher audiences due to dense populations and stronger internet access. Live and landmark sporting events are powerful viewership magnets, whether broadcast in real time or as replays. Age demographics also play a role, with younger viewers drawn to high-energy content like action, while older audiences prefer drama. Finally, the quality, variety, and relevance of Bright TV's content library remain central — programming that aligns with trending, in-demand genres has the greatest potential to grow and retain viewership.

### Recommendations

**Live & Special Events**
Secure broadcasting rights for major sporting events and concerts to drive spikes in viewership.
Live-stream popular local events exclusively on BrightTV to create urgency.

**Audience Engagement**
Introduce loyalty rewards or points systems for long-term subscribers.
Encourage user feedback and act on it to improve the overall experience.

**Pricing & Accessibility**
Offer flexible and affordable subscription packages to accommodate different income levels
Introduce free trial periods to attract new users
Partner with mobile networks to offer data-free or discounted streaming bundles


  
