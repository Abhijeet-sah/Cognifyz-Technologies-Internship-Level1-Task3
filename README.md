# Cognifyz-Technologies-Internship-Level1-Task3

# 🍽️ Restaurant Location & Rating Analysis  

## 📌 Project Overview  
This project analyzes and visualizes restaurant data using **latitude, longitude, city, country, and rating information**.  
The main goals are:  
1. **Visualize restaurant locations on a map**  
2. **Analyze the distribution of restaurants across cities and countries**  
3. **Determine correlations between restaurant location and ratings**  
4. **Discover additional insights** such as top-rated restaurants, rating distributions, and restaurant hotspots using clustering.  

---

## 📊 Features  
- 🗺️ **Interactive Map** of restaurants using latitude & longitude  
- 📈 **Distribution Analysis** across cities and countries  
- 🔗 **Correlation Study** between location and ratings  
- ⭐ **Top-Rated Restaurants** by city  
- 📦 **Boxplots** of ratings per country  
- 🔥 **Hotspot Detection** using KMeans clustering  

---

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Pandas** → Data handling  
- **Matplotlib & Seaborn** → Data visualization  
- **Folium** → Interactive maps  
- **Scikit-learn** → Clustering (KMeans)  

---

## 📂 Project Structure  

flowchart TD

    A[Load Dataset] --> B[Data Cleaning]
    
    B --> C[Visualize Locations on Map]
    
    C --> D[Distribution Analysis]
    
    D --> E[Correlation Analysis]
    
    E --> F[Extra Insights]
    
    F --> G[Top-Rated Restaurants]
    
    F --> H[Rating Distribution by Country]
    
    F --> I[Hotspot Detection with KMeans]

📸 Sample Visualizations

Restaurant Distribution by Country

<img width="996" height="572" alt="country" src="https://github.com/user-attachments/assets/dc1caf21-7b86-4082-b839-b13abc7d7ba7" />



Restaurant Hotspots (KMeans Clusters)

<img width="863" height="556" alt="hotspot" src="https://github.com/user-attachments/assets/ef21b310-8613-4439-a4f2-d6ba1218e8cd" />




📈 Results & Insights


Most restaurants are concentrated in top cities.

Certain countries dominate the dataset’s restaurant count.

Some cities have higher average ratings compared to others.

Hotspot analysis reveals clusters of restaurants in urban areas.
