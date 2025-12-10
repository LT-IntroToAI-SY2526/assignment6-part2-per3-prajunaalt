# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: 1. Bedrooms: 6648.97
2. Bathrooms: 3858.90
3. Age: 950.35
4. Least Important: SquareFeet: 121.11

**Explanation:**

You find this using the abs value from the model's coefficients. 


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional bedroom increases the price by $6648.97

**Feature 2:**
Each bathroom increases the price by $3858.90.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
0.9936. This means that our model explains 99.36% of why houses differ. There is very slight but not neccessary room for improvement.


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Stories/Floors

**Why it would help:**
Having more floors would increase the property value as there is more room than a single story home.

**Feature 2:**
Backyard (0 false, 1 true)

**Why it would help:**
Many families want a backyard and they have a large impact on price.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**

No, because you're extrapolating on everything but age, therefore there may be other external factors that alters the variability once we predict beyond the range of our data.
