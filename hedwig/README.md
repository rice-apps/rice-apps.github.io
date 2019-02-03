# Hedwig Delivery App
## Introduction
## Quickstart
## Docker Image
## Deployment
## Current Roadmap


### **_Sprint #1 (1/19)_**
Stories Done: To be updated

### **_Sprint #2 (1/26)_**
Stories Done: To be updated

### **_Sprint #3 (2/2)_**
Stories Done: To be updated

### Sem Break:
###### - Target Assigned:
1. Johnny - Work on completing the UI screens for user app - try completing 75%
2. Justin - Mutation Resolver -- complete vendor and user resolvers expect batch resolvers.
3. Will, Jeff - Finish Authentication CAS for NetID login
4. Jamie, - MobX -- complete settign up various states for the user and the order

### **_Sprint #4 (2/16)_**

Continue working on the story fro UI Screen for the user. Add more css and test navigation between screens.
Continue working on the remaining resolvers

#### **Story**
User is not able to order more than # of items in inventory
##### Acceptance Criteria
User is alerted when desired amount is > inventory; desired quantity is reduced to inventory count

#### **Story**
User is not able to order when inventory is empty

##### Acceptance Criteria
User is given a visual cue in menu when inventory is empty on an item\
If an order is placed on an item with a zero inventory, an error is thrown

#### **Story**
User is not able to order more than x items
##### Acceptance Criteria
Quantity count on user frontend does not increment past x

#### **Story**
User is shown no vendor when vendor unavailable/closed

##### Acceptance Criteria
Show vendor is closed or not functioning\
Blur out vendor details\
No action possible on that vendor\

#### **Story**
User’s CC is invalid, prompted for new credit card

##### Acceptance Criteria
Backend credit information is wiped on MongoDB\
Stripe CC information is wiped

### **_Sprint #5 (2/23)_**


#### **Story**
Vendor can adjust inventory totals from within app
##### Acceptance Criteria
-Vendor can increment inventory of an item\
-Vendor can decrement inventory of an item\
-Vendor can custom-type inventory of an item\
-Adjusted totals reflected on Stripe Dashboard

#### **Story**
Charge is transferred to vendor

##### Acceptance Criteria
Every week Vendor receives payment
Keep track of vendor total for each week


#### **Story**
User is greeted by colorful splash screen on entrance
##### Acceptance Criteria
Splash screen appears when app is initialized

#### **Story**
Screen dims and colorful loading icon appears when loading tasks occur

##### Acceptance Criteria
Universal component on frontend for loading

#### **Story**
Users can view menus of vendors separately

##### Acceptance Criteria
Each vendor has a clickable card on initial menu page that redirects to their menu\
Menu items grouped into categories by products

#### **Story**
Test app by creating atleast 5 users, 1 vendor and creating 15 orders
##### Acceptance Criteria
Vendor app is able to change inventory\
Vendor receives order\
Create, edit, delete user\
User is able to add item to cart\
User places order

#### **Story**
Market testing
##### Acceptance Criteria
- Reach out users to make them aware about the app and get initial feedback

### **_Sprint #6 (3/2)_**

#### **Story**
Backend subscription filter based on user id

##### Acceptance Criteria

#### **Story**
Backend creates event to a topic
##### Acceptance Criteria

#### **Story**
Front end subscriptions 
##### Acceptance Criteria
- to be updated

### Sem Break
### ------- 
### Work with the vendor in between these sprints - Make vendor familiar with the app.
### Vendor provides feedback on app model.
### App to be deployed on our servers for vendor to access.
### Publish app in the app store/google play

### **_Sprint #7 (3/23)_**

#### **Story**
Vendor app Testing
##### Acceptance Criteria
Try app by navigating to every screen and run functionality testing

#### **Story**
User app testing
##### Acceptance Criteria
Try app by navigating to every screen and run functionality testing

#### **Story**
Get app in the app store
##### Description
- Initialed previosuly. Complete in this sprint

#### **Story**
Market research and testing
##### Acceptance Criteria
- Reach out users to make them aware about the app and get initial feedback
- Survey customers

### **_Sprint #8 (3/30)_**
Extra sprint to take care of any scope change or use if running behind on schedule.
Also helpful in bug fixes.

#### Launch App!!!
Keep getting customer feedback
Run Analytics to understand customer behavior
Work on bugs & improvements

## Problem Space
## Solution Space


