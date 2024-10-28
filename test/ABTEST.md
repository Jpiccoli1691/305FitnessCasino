# A/B Testing 

# Team Member: Jon
## **A/B Test Name: "Color Scheme Impact on Engagement and Task Success"

## User Story Number: **US4 (The Golden Path)

## Metrics:**
- **Happiness:** Positive feedback on app aesthetics, Net Promoter Score (NPS).
- **Engagement:** Average session length, page visit counts.
- **Task Success:** Button action events, search exit rate.

- **Hypothesis:**
Suppose we apply another color scheme to the app. In that case, users will find it more visually appealing, leading to longer session times and increased interaction with app features, as other colors may improve readability and perceived usability.
- **Problem:**
  Some users find the current color scheme unappealing or hard to navigate, which could potentially impact their willingness to interact with the app.
- **Impact:** The current color scheme may deter users from staying engaged, resulting in reduced session lengths, lower engagement with app features, and overall diminished satisfaction.

- **Experiment Setup:**
  Audience: 50% of the total user base will see the new color scheme, and the other 50% will continue with the existing scheme.
  Tracking via Firebase Analytics:
    Average Session Length (Engagement): Measure any changes in time spent per session between both groups.
    Button Action Events (Task Success): Track button interaction rates for both groups to gauge user comfort with the UI.
    Page Visit Counts (Engagement): Monitor whether users are exploring different pages more with the new color scheme.
    Survey Results (Happiness): Post-experiment survey asking for user feedback on app design and color preference.
    Rationale: Testing with the full user base lets us see how existing and new users respond to the color change. This provides a broad understanding of user preferences and their impact on engagement.

- **Variations:**
Variation A: Original color scheme (e.g., darker color palette).
Design: The current color layout has all default elements.
Variation B: New color scheme (e.g., lighter color palette with higher contrast).
Design: Redesigned elements with lighter background tones, improved contrast, and easier readability.
Mockups and diagrams for both color schemes will help illustrate each variation’s interface and assist in collecting user feedback.


# Team Member: Mani
- **A/B Test Name:** Impact of progress visuals on app's fitness tracking experience
  
- **User Story Number: US4 (The Golden Path)****
  
- **Metrics:**

- **Happiness:** User satisfaction with the visual appeal and intuitiveness of the progress bars
- **Engagement:** Average number of taps or interactions with the progress bar section per session, tracked through event logs.
- **Adoption:** Percentage of users who choose to enable or switch the progress bar visuals
- **Retention:** Difference in 7-day and 14-day retention rates between users exposed to the new progress visuals vs. the control group, using retention analytics.
- **Task Success:** Successful completion of fitness tracking tasks (e.g., setting and updating goals) with the progress bar.
  
**Hypothesis:**
Enhancing the visuals of the progress bar in the fitness tracking feature will increase user engagement, as users will find the experience more motivating and visually appealing, leading to higher adoption and retention rates.
  
**Experiment:**
- Objective: Test if enhanced progress bar visuals improve engagement, adoption, and retention in the fitness tracking feature.

##1. **Groups**
   
- Control Group: Standard (horizontal) progress bar design.
- Test Group: Circular bar design.
  
##2. **Metrics (Tracked via Firebase Analytics)**

- Engagement: Track interactions with the progress bar (progress_bar_interaction event).
- Adoption: Monitor customizations (progress_bar_customization_enabled event).
- Retention: Measure 7-day and 14-day retention via cohort data.
- Task Success: Track goal completions (goal_set_complete event).
  
##3. **Method**
  
- Use Firebase Remote Config to randomly assign users to control or test groups.
- Run for 2 weeks, analyze differences in engagement, adoption, and retention.
- Expected Outcome: Test group shows higher engagement and retention due to improved visual appeal.
  
**Variations:**
- Variation A: A horizontal progress bar design
- Variation B: A circular progress bar design
  

# Team Member: Matthew
## A/B Test Name: In-Game Store vs. Profit Tracker for User Retention

## User Story Number: **US4 (The Golden Path)**

### **Metrics:**

- **Happiness:** User satisfaction scores related to the rewards and tracking experience.
- **Engagement:** Time spent on the rewards store vs. profit tracking page.
- **Adoption:** The percentage of users who interact with either the rewards store or profit tracker.
- **Retention:** Users returning to the app after engaging with the store or tracker within a specified time frame.
- **Task Success:** User actions taken after engaging with either feature, like redeeming rewards or betting more tokens.
- **Hypothesis:**
If users are provided with an in-game rewards store, they will feel more motivated to participate in activities that earn tokens, leading to higher retention rates compared to those who only have an in-game profit tracker. This is because users are more likely to engage with tangible rewards that can be redeemed, enhancing the overall gaming experience and encouraging them to return to the app frequently.

### **What problem are we trying to solve? Its impact?**

**Problem:** Users may lose interest if the app lacks engaging incentives for continued play. While tracking profit is informative, it may not provide enough motivation for users to keep playing and earn tokens.

- **Impact:** By introducing a rewards store, we aim to boost user retention. Users often respond well to visual incentives and tangible rewards, which could lead to more frequent app usage and a stronger community. This ultimately helps retain existing users and reduces churn rates.

### **Experiment:**

#### 1.  **Audience:**

- 50% of users will be assigned to Variant A (access to the in-game rewards store).
- 50% of users will be assigned to Variant B (access to the in-game profit tracker).
- Rationale: This split allows for a direct comparison of engagement and retention related to tangible rewards versus tracking information.

#### 2. **Tracking in Firebase Analytics:**

- Track interactions with the rewards store and profit tracker, including time spent on each page and the number of tokens redeemed or tracked.
- **HEART Metrics Tracking:** Specifically track the Rewards Store Interaction Count, Profit Tracker Interaction Count, and Return Frequency for each group to evaluate how each feature influences user retention.

### **Variations:**

#### 1. **Variation A: In-Game Rewards Store**

- Users can browse and redeem cosmetic items, bonuses, or tokens for gameplay enhancements.

- Mockup: A visually appealing rewards store interface that displays available items, their costs in tokens, and redemption options.

#### 2. **Variation B: In-Game Profit Tracker**

- Users can see their token earnings, betting history, and overall performance metrics without direct incentives.

- Mockup: A clean layout showing historical data and token profit over time, possibly with graphs and stats.
After running the test, analyze which variant leads to higher retention rates and user engagement. If Variation A (the rewards store) shows significantly higher retention and engagement metrics, it could justify further investment in developing and enhancing the rewards system within your app.

# Team Member: Peter
- **A/B Test Name:**
- **User Story Number:**
- **Metrics:**
- **Hypothesis:**
- **Experiment:**
- **Variations:**
  
