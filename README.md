# Taxi Trip Data Visualization (Linked View using altair)

Author: Uday Bhaskar Voora

## Dataset Description

The dataset contains taxi trip records with various attributes, including:

- **Pickup Community Area** (numeric ID of the area where the trip started)

- **Payment Type **(e.g., Cash, Credit Card, etc.)

- **Trip Duration (seconds)** (time taken for each trip)

- **Trip Count** (total number of trips per Payment Type)

### Line Chart: Average Trip Duration by Pickup Community Area

X-axis: Pickup Community Area (randomly selected 50 areas)

Y-axis: Average trip duration in seconds

Color: Represents different Payment Types

**Interactive Feature:**

- Users can drag/brush over the x-axis (Pickup Community Area) to select specific areas.

- The selected areas filter the data shown in the bar chart.

- Bar Chart: Number of Trips by Payment Type

- X-axis: Payment Type (Cash, Credit Card, etc.)

- Y-axis: Number of trips for the selected community areas

**Interactive Feature:**

- The bar chart updates dynamically based on the selected Pickup Community Areas in the line chart.


**Takeaway from this visualization:**

- This visualization provides interactive insights into the relationship between Pickup Community Areas, trip durations, and payment methods. The ability to filter data dynamically allows for a more detailed understanding of taxi service patterns across different areas.

