# Composite Material Tensile Strength Dataset

<img width="225" height="225" alt="Image" src="https://github.com/user-attachments/assets/3d324be5-4167-43ec-9ea4-5ed7a386df20" />

This README is designed to provide a professional overview of the data analysis, focusing on the performance of different fiber and resin combinations as shown in this visualization.
## Composite Material Tensile Strength Analysis
### Project Overview
This dataset analyzes the *tensile strength (MPa)* of various fiber-reinforced polymers (FRP). The primary objective is to evaluate how different combinations of fiber types and resin matrices affect the structural integrity and mechanical performance of the resulting composite material.
### Dataset Description
The analysis tracks the average tensile strength across a matrix of materials:
 Fiber Types:* Aramid, Basalt, Carbon, and Glass.
 Resin Matrices:* Epoxy, Phenolic, Polyester, and Vinyl Ester.
### Key Insights
 Optimal Combination:* Carbon Fiber paired with Epoxy resin yields the highest tensile strength, exceeding *2,700 MPa*.
 Resin Performance:* Epoxy consistently outperforms other resin types across all fiber categories, indicating superior interfacial bonding.
 Material Ranking:*
   1. *Carbon:* High-performance applications.
   2. *Aramid:* High strength-to-weight and impact resistance.
   3. *Basalt:* Sustainable, mid-range structural performance.
   4. *Glass:* Cost-effective, general-purpose reinforcement.
### Technical Visualization
The data is visualized through a grouped bar chart, allowing for a direct comparison of how a specific resin influences the tensile properties of different fibers.
| Variable | Description |
|---|---|
| fiber_type | The reinforcing agent (Independent Variable) |
| resin_type | The polymer matrix (Grouping Variable) |
| tensile_strength_mpa | The measured stress until failure (Dependent Variable) |

Business Questions and  Result Interpretations

Based on the technical trends identified in the dataset, here are six business questions designed to bridge the gap between material performance and operational decision-making:

Question 1. Product Optimization & R&D
Given that Carbon-Epoxy combinations yield the highest tensile strength, what is the cost-to-benefit ratio of switching from Aramid or Basalt to Carbon for our mid-tier product lines?"
  Purpose: To determine if the performance gains justify the likely increase in raw material costs for products that may not strictly require maximum strength.
Answer: This chart illustrates that increasing the fiber volume fraction yields a statistically significant increase in tensile strength, it is not the sole determinant of performance. To optimize mid-tier products,  focus should on maintaining a V_f between 0.50 and 0.60 while prioritizing the reduction of voids to tighten the vertical variance seen in the data.

Question 2. Manufacturing Efficiency
How does the increase in layer count impact our total production time and energy consumption per unit compared to the resulting gain in tensile strength?
  Purpose: To find the "sweet spot" in manufacturing where we achieve required safety margins without over-engineering the product and wasting machine hours.
 Answer: This chart illustrates the average tensile strength of various fiber-reinforced polymers (FRPs) by comparing four fiber types across four different resin matrices.
Across all resin types, Carbon fiber consistently exhibits the highest tensile strength, peaking at approximately 2,750 MPa when paired with Epoxy. It significantly outperforms Aramid, Basalt, and Glass fibers in every category.
If the goal is to maximize tensile strength, the combination of Carbon fiber and Epoxy resin is the clear winner. Conversely, using Glass fiber with Polyester resin results in the lowest tensile strength, which might be acceptable for non-structural or budget-constrained applications.

Question 3. Quality Control & Waste Reduction
What is the financial impact of 'Void Content' on our scrap rate, and at what percentage does it cause a statistically significant drop in strength that leads to part failure?"
 Purpose: To establish strict QA/QC thresholds for void content and determine if investing in better vacuum-bagging or curing equipment would pay for itself through reduced waste.
Answer: The trendline shows a positive correlation (0.33 of this data  ). this shows the point where the resin is perfectly saturating the fibers; as more fiber is added  (the load-bearing element), the strength increases, provided the "void content" stays low.

Question 4. Supply Chain Diversification
If we face a shortage of Epoxy resin, which alternative resin (Vinyl Ester, Phenolic, or Polyester) maintains the most consistent performance standards when paired with our current fiber types?"
 Purpose: To create a data-driven contingency plan for the supply chain that minimizes the risk of product recalls or performance downgrades.
Answer: From the table, Red typically represents a strong negative correlation (like Void Content vs. Strength).    Blue/Green represents a strong positive correlation (like Layer Count vs. Strength).    White represents little to no correlation (near 0).
 It instantly shows that Layer Count (0.64) and Fiber Volume (0.33) are primary strength drivers, while Void Content (-0.23) is the main "strength killer"  needed to monitor in quality checks.

Question 5. Market Positioning
Can we develop a 'High-Efficiency' product line using Glass fiber and Epoxy that matches the strength of Basalt-Polyester but at a lower weight or price point?"
Purpose: To use the data to find unconventional material pairings that might offer a competitive advantage in price-sensitive markets.
Answer: The Box Plot tells more than a simple bar chart. While a bar chart only shows the average, the Box Plot shows the consistency of the material:  The height of the box: Shows the "Interquartile Range" (where the middle 50% of the samples fall). A shorter box means the material is very consistent.  The "Whiskers": Show the total range of the data.  The Dots (Outliers): These are the "red flags." In a QA/QC context, outliers on the bottom end represent parts that might have failed due to high void content or curing issues.
The red trendline slopes upward, which confirms a positive correlation.

Question 6. Process Standardization
Does the data suggest a 'diminishing return' for curing temperatures above a certain threshold, and can we lower our standard curing temperature to save energy without compromising structural integrity?"
  Purpose: To optimize the curing cycle for sustainability and cost reduction while maintaining the physical properties required by engineering specifications. 
Answer: This chart illustrates the relationship between Curing Temperature and the Mean Tensile Strength (measured in MPa) for four different types of resins.
Across all four resin types, there is a positive correlation between curing temperature and tensile strength. As the temperature increases from the 60–80°C range to the 140–160°C range, the mean tensile strength consistently rises. This suggests that higher curing temperatures generally improve the cross-linking or bonding efficiency of these materials.
The slope of the lines indicates how sensitive each resin is to temperature changes.

### Applications
The findings from this analysis are critical for material selection in:
 Aerospace & Automotive:* Prioritizing Carbon/Epoxy for weight reduction and high stress.
 Civil Engineering:* Utilizing Basalt or Glass for infrastructure reinforcement where cost and corrosion resistance are key.
 Marine:* Evaluating Vinyl Ester for its balance of strength and moisture resistance.
### How to Use This Repository
 1. *Data:* View the raw results in the /data folder.
 2. *Analysis:* The Excel/Power BI source files used to generate the charts are located in /visualizations.
 3. *Usage:* Refer to the summary table for quick material specification references.
  
you can reach me via Peterimhonikhe50@gmail.com
