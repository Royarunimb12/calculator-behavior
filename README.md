# Calculate Behavior

This project works out five features of a calculator:

1. Addition
1. Multiplication
1. Division
1. Subtraction
1. Power-on and power-off

Each feature would consist of scenarios.
Capture each scenario as:

- initial condition (Given...)
- event (When...)
- effect (Then...)

Each feature is in a different markdown file.
This template has one blank starting point.

As always, avoid passive voice :)

#Scenarios
Scenario: Add two numbers
Given I have a calculator that's turned on.

 When I enter "number1"
And I press "+" button
And I enter "number2"
And I press "=" button
Then I see the "added sum" as the result
