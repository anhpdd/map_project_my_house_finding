# Introduction
Hello, I'm Duy Anh, a bachelor's graduate from Vietnam. In this project, I aim to analyze and find the most convenient housing locations in Malaysia, specifically near Sunway University, where I will be pursuing my education.

# Project Goal
The goal of this project is to determine the most suitable house for me to rent, based on the following criteria:

- Distance to Sunway University by bike.
- Travel time from the house to Sunway University.
- Rent price under RM 3000.

In short, the ideal house should be both affordable and close to the university.

# Tools Used
**Route Optimization:** OpenRoute Service
**Data Analysis:**
  - Pandas
  - Excel
  - ...

**Web Crawling:**
- Beautiful Soup


# Project Steps
**Step 1:** Data Collection
Data is collected from iproperty.com.my, with filters applied to meet specific requirements. In my case, I was looking for houses with at least 3 bedrooms.

**Step 2:** Data Cleaning
**Step 3:** Data Analysis
We use Excel's Pivot Table to group households by apartment complexes, as multiple units within the same apartment can have different prices. This also helps in locating apartments more effectively than handling individual households.
Filter out houses with rent prices above RM 3000.
After filtering, I was left with around 200 apartments. I manually entered the coordinates for these apartments. In the future, I hope to find a tool to automate this geocoding process.

# Final Results
We visualize all the filtered apartments on a map, showing their respective routes. In this project, I focused on the 70 closest apartments.
![image](https://github.com/user-attachments/assets/669a8b10-3d64-4e3b-912e-97a3387427b0)

Additionally, individual routes can be visualized for specific apartments. Below, I have visualized the routes from the 3 closest apartments.
![image](https://github.com/user-attachments/assets/937f6072-9584-48bb-ae9d-4eb476dc4a54)

You can also click on each map marker to view more details about the apartment.
![image](https://github.com/user-attachments/assets/565dbc27-1c21-40ed-a7b1-2548c0992692)

-----

Feel free to contact me for further improvements upon the project: duyanh.phanduc@gmail.com
Thank you.

