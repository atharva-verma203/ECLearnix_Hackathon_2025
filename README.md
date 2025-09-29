# 🏆 ECLearnix Hackathon 2025

## 📊 Overview
*	**Situation** : EdTech platform with 100K+ users, facing low long-term app engagement, LMS course drop-offs, uneven event participation

*	**Task** : To analyze 3 years of user activity, which includes event registration, feedback, and marketing data; To predict user behaviour; To identify loyal vs. inactive users; To segment audiences to personalize the learning journey.

*	**Action** : Exploratory Data Analysis (EDA), Clustering, Predictive Modeling, Dashboards, Strategy Recommendations

*	**Result** : To scale from 100K to 1M+ users, optimize marketing ROI, and become India’s most data-driven learning platform.

* **Tools** : Python (pandas, numpy, matplotlib, seaborn, scikit-learn), R (dplyr, tidyr, ggplot2), Power BI (with custom visuals using R script)

## 📋 Methodology
* **Exploratory Data Analysis (EDA)** : Handling missing values in data, Univariate and Bivariate Analysis (with summary and key metrics), Data Visualization.

* **User Segmentation (Clustering)** : To identify distinct user segments based on behavioral patterns for targeted strategies with the help of **K-Means clustering using Elbow and Silhouette Methods**.

* **Predictive Modeling** : To predict course completion and app retention rates using models like **Logistic Regression, Random Forest, Support Vector Machines (SVM), Gaussian Naïve Bayes**.

* **Marketing ROI Analysis** : To identify which platform source yields highest course completion rate.

* **Conversion Funnel Assessment** : To provide a comprehensive view of user progression through key stages, identifying drop-off points and associated user behavior metrics at each stage.

* **Dashboard Implementation** : To visualize KPI metrics like **Conversion Rate by Marketing Channel**, **30-Day User Retention Rate**, **Feedback Rating**, etc.

* **Recommendations and Strategies** : To provide recommendations and strategies along with a roadmap for implementation purposes.

## 🔍 Key Insights
* **High Inactivity** : **~74% of users inactive after 30 days post-login** indicating significant retention issues.

* **Onboarding Friction** : A critical **~6.6% drop-off between app install and first login**, signaling a need for streamlined onboarding.

* **Diverse User Segments** : Identification of distinct user clusters (e.g., High Engagers, Churn Risks) enabling personalized strategies.

* **Predictive Power** : Models accurately identify users at risk of not completing courses or churning, allowing for proactive interventions.

    _Note :_ The overall accuracy for different models lies in the range **50-60%**, indicating _the data might be synthesized and may not reflect real life observations._

* **Platform ROI Variation** : Significant differences in conversion rates across marketing platforms, highlighting opportunities for optimized advertisement spend.

## 💡 Recommendations and Suggestions
*	**First-Login Sprint (_Fix the install → first-login drop_)**
    *	What: Simplify the first-run experience: single-tap login, skip/preview course flow, instant “start a 2-minute lesson” option.
    
    *	Why: You lose **~6.6% between install and first login**. Small friction here costs long-term engagement.
    
    *	Quick Win: Add an “instant mini-lesson” on first open to show value.

*	**Predict & Nudge (_Churn Prediction + Smart Nudges_)**
    *	What: Identify users likely to go inactive and send tailored nudges (timed reminders, one-click micro-tasks, or offers).
    
    *	Why: **74% inactive after 30 days** — targeted nudges beat blanket messaging.
    
    *	Quick Win: Send a “We miss you” micro-lesson + progress reminder for users who haven’t opened the app in 7 days.
    
*	**Micro-Learning & Completion Paths**
    *	What: Break courses into **5–10 minute micro-lessons**, show “next best micro-lesson” and allow one-tap resume.
    
    *	Why: Course completion is **~49.9%** — smaller steps reduce drop-off and create momentum.
    
    *	Quick Win: Convert 1-2 long modules into micro-lessons and measure completion lift.
    
*	**Cohort Catalyst (_Community + Events to Drive Retention_)**
    *	What: Turn registrants into active cohorts — small study groups, fixed-schedule live sessions, peer badges.
    
    *	Why: Event registration doesn’t always mean attendance; cohorts create social pressure and accountability.
    
    *	Quick Win: Run a 1-week cohort for a top course with chat + daily micro-assignments.

*	**Channel Smart Allocation (_Marketing Matchmaker_)**
    *	What: Re-allocate marketing budget toward channels that produce more engaged learners (**YouTube & LinkedIn show ~41% completion**). Run experiments to confirm.
    
    *	Why: Not all users are equal — some channels bring higher-quality learners.
    
    *	Quick Win: Increase trials on YouTube/LinkedIn ads and add a “learners from X channel” tag to measure the loan-to-value ratio (LTV)/engagement.

## 🎯 Roadmap and Future Scalability
* **Immediate Actions (First 3 Months)** :
    * Deploy streamlined, segment-specific onboarding flows to address low first-login drop-off

    * Implement intelligent notification systems targeting inactive users
    
    * Optimize high-performing acquisition channels like YouTube and LinkedIn

* **Medium-term Initiatives (3-6 Months)** :
    * Launch comprehensive gamification framework to improve satisfaction rating

    * Deploy AI-powered content recommendation engine addressing completion drop-off

    * Establish community learning hubs leveraging event registration engagement

* **Long-Term Transformation (6 Months - 1 Year)** :
    * Achieve higher app installation rates through platform-optimized campaigns
    
    * Reach higher levels of course completion through personalized learning pathways
    
    * Establish 30-day retention through community-driven engagement

## 📈 Conclusion
In conclusion, our data-driven approach illuminated key challenges in ECLearnix's user engagement and provided actionable insights for sustainable growth. By implementing personalized strategies derived from user segmentation, optimizing the conversion funnel, and leveraging predictive analytics, we found that the platform could significantly enhance user retention, boost course completion, and maximize marketing ROI. For example, utilizing platforms like YouTube and Instagram with Shorts and Reels, LinkedIn with promotional posts, word-of-mouth, phygital learning strategies and corporate tie-ups, etc., it would be possible to utilize the best methods for social media management to cover promotions for the platform to larger networks.
