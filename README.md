# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

[Erick Cho](https://github.com/ec3566)  
[Micheal Lin](https://github.com/freerainboxbox)  
[Ahmed Omar](https://github.com/ahmed-o-324)  
[Henry Wang](https://github.com/fishlesswater)  

## Stakeholders

### Stakeholder: Jae Yoon 
##### Goals:  
1. To get where they need to go with consideration for their handicap.
2. Find out how accessible the location they wanted to visit was.
3. Route planner that takes into account their specific handicap.
##### Concerns:
1. Accuracy of the accessibility information.
2. State of the amenities.

## Product Vision Statement

A crowdsourced accessibility focused navigation app where users can tailor routes to accomodate for their specific needs and collectively update a location's accessibility information.

## User Requirements

### As a user, I want to filter for restaurants that are wheelchair accessible so I can go out with my friends.
Estimation of effort: L  
Acceptance criteria:
1. User's accessibility needs are available to be selected.
2. User's accessibility profile is saved.
3. User's accessibility profile is private.
4. All restaurants that are wheelchair accessible are displayed.


### As a user, I want to plot a route for the visually impaired so I can more easily make my way to my destination.
Estimation of effort: M  
Acceptance criteria:
1. User's starting point is captured and saved.
2. User's destination is captured and saved.
3. A route using public transportation with amenities for the visually impaired is displayed.
4. If a complete route cannot be made, sections without amenities are indicated.


### As a user, I want to update a location's accessibility information so I can contribute to the app (this one needs better wording)
Estimation of effort: L  
Acceptance criteria:
1. An "update location amenities" button is visible.
2. A menu pops up when the button is pressed.
3. Users can select and deselect amenities.
4. Information is saved to the server.
5. If enough changes are indicated by users, the location's information is updated for all users of the app (with a confidence score).


### As a business, I want to update my location's accessibility information so I can attract more people to my place of business.
Estimation of effort: L  
Acceptance criteria:
1. Proof of ownership must be captured.
2. Ownership must be verified.
3. Business is now prompted to adjust and change its accessibility information as they please.
4. Information is uploaded to the server and weighted more than anonymous users.


### As a user, I want to share a location's accessibility availability to my friends and family so I can help them get somewhere.
Estimation of effort: L  
Acceptance criteria:  
1. Location's accessibility information is displayed for the user.
2. User clicks a share button.
3. A menu pops up with links to relevant social media platforms where the user can share the information.
4. A premade message listing the accessibility information of the location is sent through the social media of choice.

### As a user, I want to be guided through a route so I can get to where I need to go.
Estimation of effort: L  
Acceptance criteria:
1. User's starting point is captured and saved.
2. User's destination is captured and saved.
3. Server checks user's accessibility preferences.
4. A route is generated for the user.
5. User clicks "Start Route".
6. User is guided through the route, with voice if indiciated that it is necessary.
7. User reaches their destination and a pop up asking about the accuracy of the accessibility information is raised.
8. User answer is captured and saved, and any errors noted.

## Activity Diagrams

See instructions. Delete this line and place images of your UML Activity diagrams here.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.
