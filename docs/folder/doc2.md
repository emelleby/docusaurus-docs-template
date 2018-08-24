---
id: folder.doc2
title: Period selection
---
**Choose period to be billed**

This is where the user can choose the period of payment for subscription. 

<iframe style="border: none;" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FTu5EQzChVPSCFZ1T7xsC0fw6%2Fsignup%3Fnode-id%3D294%253A3081" allowfullscreen></iframe>

This is a link to the **<a href="https://zpl.io/aMvPpRK" target="_blank">Zeplin page.</a>**

---

**Charts from RealTimeBoard**

<iframe width=100% height="720px" src="https://realtimeboard.com/app/embed/o9J_kzAKsVw=/?moveToWidget=3074457346179286569" frameborder="0" scrolling="no" allowfullscreen></iframe>



## Screen

| Element | Type | Action | Criteria |
| -------- | ---- | ------ | -------- |
| Choose monthly | Button | Link to public signup page for the monthly product | https://teo-no-clone.chargifypay.com/subscribe/9th2ctbmvyn8/no-payg |
| Choose quarterly | Button | Link to public signup page for the quarterly product | Link coming soon. Make sure it is the right market |
| Choose yearly | Button | Link to public signup page for the yearly product |Link coming soon. Make sure it is the right market |
| Close popup | button | close popup | back to product page |


## Story: Choose periode
| Number | Theme | Priority | As the.. | I want to... | So I can...|
| :----: | ----- | -------- | ------------- | ------------ | -----------|
| 001 | Signup | High | User | be able to sign up for a monthly plan | pay on a monthly basis and churn every month if so. |
| 002 | Signup | High | User | be able to sign up for a quarterly plan | save some by paying 3 months up front. 10% |
| 003 | Signup | High | User | be able to sign up for a yearrly plan | save some by paying 12 months up front. 20% |
| 004 | Signup | High | User | see how much I will have to pay now for the monthly, quarterly and yearly plan | be prepared for the pain. |
| 005 | Signup | High | User | see what the monthly cost on average is for the quarterly and yearly plan | see how much I save a month for these plans.|
| 006 | Signup | High | User | see how much I save each period in total for the quarterly and the yearly plan in comparison to being on the monthly plan. | feel good when I go for the yearly plan. |

---

## BDD scenarios

### Online-001-001: User lands on page first from the Apprentice signup button
| | |
| --- | --- |
| **Given** | the user has clicked the apprentice signup button |
| **And** | |
| **When** | the popup screen loads |
| **Then** | it will show the three Apprentice period options |
| **And** | the prices are calculated correctly - Quarterly is (price*0.9*3) & Yearly is (price*0.8*3) |
| **And** | the calculated savings are correct |

### Online-001-002: User lands on page first from the Master signup button
| | |
| --- | --- |
| **Given** | the user has clicked the Master signup button |
| **And** | 
| **When** | the popup screen loads |
| **Then** | it will show the three Master period options |
| **And** | the prices are calculated correctly - Quarterly is (price*0.9*3) & Yearly is (price*0.8*3) |
| **And** | the calculated savings are correct |

### Online-001-003: User navigates away from popup
| | |
| --- | --- |
| **Given** | the user has clicked the Master or Apprentice signup button |
| **And** | The popup loads
| **When** | user clicks the X in the top right corner or outside the popup |
| **Then** | the popup will close |
| **And** | the user is back on the product page |


This is a link to [another document.](doc3.md)  
This is a link to an [external page.](http://www.example.com)
