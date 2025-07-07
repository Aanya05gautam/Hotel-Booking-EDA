# 🏨 Hotel Booking Analysis

This project provides an in-depth analysis of hotel booking data using Python. The main goal is to explore customer behavior, booking trends, and cancellation patterns using visualizations created with Pandas, Matplotlib, and Seaborn. It’s ideal for data enthusiasts, analysts, and students looking to practice data cleaning, aggregation, and visualization.

---

## 📦 Dataset

The dataset includes hotel booking records from both city and resort hotels. It contains features such as:

- `hotel` – City Hotel or Resort Hotel  
- `is_canceled` – Booking status  
- `lead_time` – Number of days between booking and arrival  
- `stays_in_weekend_nights`, `stays_in_week_nights` – Length of stay  
- `country` – Country of origin  
- `guests` – Number of adults, children, babies  
- `special_requests`, `deposit_type`, and more

---

## 📊 Key Visualizations

1. **Cancellation Rate by Hotel Type**  
   A bar chart showing the percentage of bookings canceled at each hotel type.

2. **Length of Stay Distribution**  
   A histogram displaying how long guests stay, separated by hotel type.

3. **Top 10 Countries by Booking Count**  
   A bar chart showing the top countries from where bookings originated.

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## 📁 Project Structure

```bash
hotel-booking-analysis/
│
├── Hotel_Booking_Analysis.ipynb    # Jupyter Notebook with all analysis and visualizations
├── README.md                       # Project overview and documentation
├── requirements.txt                # Python libraries required
└── dataset/                        # (Optional) Folder to store the CSV data

