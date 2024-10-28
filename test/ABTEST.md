# A/B Testing 

# Team Member: Jon
- **A/B Test Name:**
- **User Story Number:**
- **Metrics:**
- **Hypothesis:**
- **Experiment:**
- **Variations:**

# Team Member: Mani
- **A/B Test Name:**
- **User Story Number:**
- **Metrics:**
- **Hypothesis:**
- **Experiment:**
- **Variations:**

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
## A/B Test Name: Strava Integration Placement for Improved User Adoption

## User Story Number: **US3 Backend Setup**

### **Metrics:**

- **Adoption:** Rate of users completing Strava integration.
- **Engagement:** Frequency of interactions with fitness features post-integration.
- **Retention:** Comparison of return rates between users who complete Strava integration vs. those who don’t.
- **Task Success:** Rate of active users on fitness-tracking features.

### **Hypothesis:**
If Strava login is introduced during onboarding, users are more likely to complete the integration and engage with fitness tracking features, compared to when Strava setup is available only in settings. Immediate exposure during onboarding highlights Strava benefits early, potentially increasing adoption and fitness feature engagement.

### **What problem are we trying to solve? Its impact?**

**Problem:** Users may skip Strava integration if it is introduced only as a later option in settings, leading to lower adoption and engagement with fitness features.

- **Impact:** Placing Strava login in onboarding could drive higher adoption and retention. Increased use of fitness features may enhance user experience, promoting app engagement and reducing churn.

### **Experiment:**

#### 1. **Audience:**

- 50% of users are assigned to Variant A (Strava login in onboarding).
- 50% of users are assigned to Variant B (Strava login in settings).
- **Rationale:** A split approach allows a direct comparison of integration rates, engagement, and retention across early versus deferred Strava setup.

#### 2. **Tracking in Firebase Analytics:**

- Track Strava integration completion rate, engagement with fitness features, and user retention.
- **HEART Metrics Tracking:** Monitor **Strava Integration Completion Rate, Fitness Feature Interaction Count**, and **Return Frequency** for each group to evaluate Strava placement’s effect on retention.

### **Variations:**

#### 1. **Variation A: Onboarding Integration Prompt**

- Users see Strava login as part of onboarding, highlighting benefits like workout syncing and in-game rewards.
- **Mockup:** An onboarding screen with a prominent Strava login button and fitness feature benefits description.

#### 2. **Variation B: Settings Integration Prompt**

- Users can access Strava login only via the settings menu post-onboarding.
- **Mockup:** A settings layout where users see Strava login under “Fitness Integration,” with a similar description of benefits.

After the test, assess which variant has higher Strava integration and user engagement with fitness features. If **Variation A** shows increased adoption and engagement, it suggests onboarding placement effectively enhances user interaction with fitness tracking.

**Variations:**  
- **Variation A (Control):** Current app color scheme (e.g., soft pastels with low contrast between background and CTA buttons).
- **Variation B (Test):** High-contrast color scheme (e.g., bold colors for CTAs with increased contrast against the background). 

The results will determine if a change in color scheme can enhance user engagement and adoption of premium features.
