# COVID-19 Analysis
<img src="./images/img.jpg">
<style>
    .image-row {
        display: flex;
        justify-content: center;
        margin-bottom: 20px;
    }
    .image-container {
        flex: 50%;
        padding: 10px;
    }
    .image-container img {
        width: 100%;
        display: block;
        margin: 0 auto;
    }
</style>
---

## Coronavirus
The coronavirus or Covid-19 is a large family of viruses that causes illnesses ranging from the common cold to acute respiratory syndromes, but the current virus is a novel strain not seen before. Common symptoms of the novel coronavirus strain include respiratory symptoms such as fever, cough, and shortness of breath, according to the WHO. The WHO has declared the coronavirus epidemic as a global health emergency.

---
# **This project shows the affect of coronavirus India wide and World Wide.**

---
## Getting Started:
- Install python
- Install jupyter notebook and connect to ipynb-kernel

---
## Requirements:
#### ```pip install pandas matplotlib seaborn plotly folium```
## TechStack:
- #### **`pandas`** for dataframes
- #### **`matplotlib`** for visualizing plots
- #### **`seaborn`** for visualizing plots
- #### **`plotly.express`** for visualizing plots
- #### **`plotly.graph_objects`** for visualizing charts
- #### **`folium`** for visualizing maps

---
## Outline:

---
### Part-1: Covid Cases in India
#### 1.1 Plot Visualization:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_india/1.png" alt="1">
    </div>
    <div class="image-container">
        <img src="./images/covid_india/2.png" alt="2">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_india/3.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_india/4.png" alt="4">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_india/5.png" alt="5">
    </div>
</div>

#### 1.2 Seaborn Visualization:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_india/sns.png" alt="3">
    </div>
</div>

#### 1.3 Geographical Visualization:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_india/map.png" alt="3">
    </div>
</div>

### Part-2: Cumulative Analysis of India with South Korea, Italy, Wuhan
<div class="image-row">
    <div class="image-container">
        <img src="./images/cumulative_cases/1.png" alt="3">
    </div>
</div>

### Part-3: World wide Covid Cases Analysis
#### 3.1 Tree Map Visualization:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/TotalCases.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/TotalDeaths.png" alt="5">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/TotalRecovered.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/ActiveCases.png" alt="6">
    </div>
</div>

#### 3.2 Observing Trend:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/Trend.png" alt="3">
    </div>
</div>

#### 3.3 Population to TestsDone Ratio:
<div class="image-row">
    <div class="image-container">
        <img src="./images/PopTest.png" alt="3">
    </div>
</div>

#### 3.4 Top 25 countries that are badly effected by Covid-19:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/bad.png" alt="3">
    </div>
</div>

#### 3.5 Worst 20 countries:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/maxConf.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/maxDeath.png" alt="4">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/maxActive.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/maxRec.png" alt="4">
    </div>
</div>

#### 3.6 Pie Chart Vizualization:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/pie+TotalCases.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/pie+TotalDeaths.png" alt="5">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/pie+TotalRecovered.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/pie+ActiveCases.png" alt="6">
    </div>
</div>

#### 3.7 Ratio Bar plots of all countries:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/DtoCon.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/DtoRec.png" alt="5">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/TesttoCon.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/SerioustoDeath.png" alt="6">
    </div>
</div>

#### 3.8 Each Country Vizualisation:
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/US.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/Russia.png" alt="5">
    </div>
</div>
<div class="image-row">
    <div class="image-container">
        <img src="./images/covid_world/India.png" alt="3">
    </div>
    <div class="image-container">
        <img src="./images/covid_world/Brazil.png" alt="6">
    </div>
</div>

### Part-4: Time series World Wide Covid Cases Analysis
#### 4.1 Plotting the Trend by date:
<div class="image-row">
    <div class="image-container">
        <img src="./images/time_series/trend.png" alt="3">
    </div>
</div>

#### 4.2 Time Lapse
![1](./images/time_series/time_lapse.gif)
**Watch the video [here](./images/time_series/time_lapse.mp4)**