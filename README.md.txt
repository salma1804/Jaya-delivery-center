# Jaya Delivery Center Optimization

## 📌 Overview  
This project uses the **Jaya algorithm** to find an optimal location for a delivery center such that the total distance to all customers is minimized.  
The algorithm moves candidate locations toward the best and away from the worst solution in each iteration.

## 🧮 Problem Statement  
Given a set of customer locations \((x_i,\,y_i)\), we want to find the delivery center location \((x,\,y)\) that minimizes:  
\[
\sum_{i=1}^{n} \sqrt{(x - x_i)^2 + (y - y_i)^2}
\]

## 🛠️ Solution Approach  
- Implemented the Jaya algorithm: maintain a population of possible centers, identify the best and worst candidates each iteration, update all candidates accordingly.  
- Written in Python using `matplotlib` for visualization.  
- Demonstrates the movement of the delivery center toward the optimal position.

## 📋 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/YourUsername/YourRepoName.git
