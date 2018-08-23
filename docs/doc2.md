---
id: doc2
title: Test
---

![Screenshot][Picture]

[Picture]: https://weareint.invisionapp.com/static-signed/live-embed/199936544/275207496/1/latest/dN37a9Zh0qyFAzoHlD2Z2z0Zr9mUl8WcKMz1ZYxI2V9lVRRlEwkE5Q804eJAac0qxblEnfcJXVd5X8P5lLUutFglE/1.1.2-2x.png

Invision URL: https://weareint.invisionapp.com/d/#/console/11462273/272949439/preview

# Description
## Setup your account 1
This is the setup wizard screen and it will show the steps that the user will go through to set up the account/workspace. To incourage users to setup as much as possible we will have some guiding on how far they have come. This will be in percent of completness regarding the recommended setup.

![Screenshot][url] Optional

[url]: 

[Charts][Charts URL]

[Charts URL]: ../../Charts/Exports/index.html

<iframe src="https://realtimeboard.com/app/embed/o9J_kzAKsVw=/?moveToWidget=3074457346179286569" frameborder="0" scrolling="no" allowfullscreen></iframe>
# Screen

| Element | Type | Action | Criteria |
| -------- | ---- | ------ | -------- |
| Setup step 1 | Expanded List | Move to step | Will show progress on setup information recommended |
| Complete company information | Checkbox/Link/Button | Navigation | Will change color and a checkmark will visualize the progress along with a percentage |
| 5 more steps | Checkbox/Link/Button | Will change color and a checkmark will visualize the progress along with a percentage |


## TEO-002: Setup account overview
| Number | Theme | Priority | As the.. | I want to... | So I can...|
| :----: | ----- | -------- | ------------- | ------------ | -----------|
| 001 | Setup | High | User | Access the different information that is recommended to provide as I start my subscription | have things setup |
| 002 | Setup | High | TEO | have the customer provide information about themselves and setup the account as much as possible | make sure they invest into the system and will have things sorted when they will go on |
| 003 | 
| 004 | 

---

## BDD scenarios

### TEO-001-001: User lands on page first time
| | |
| --- | --- |
| **Given** | the user has signed up |
| **And** | this is the first time they login
| **When** | the first page screen loads 
| **Then** | it will show setup wizard 
| **And** | the percentage is 15% based on mandatory information provided

### TEO-001-001: User comes back to the page after navigating away
| | |
| --- | --- |
| **Given** | Is signing in
| **And** | the completion percent is below 40%
| **When** | the first page loads 
| **Then** | it will setup your account page 
| **And** | a red bar is showing the setup percent

This is a link to [another document.](doc3.md)  
This is a link to an [external page.](http://www.example.com)
