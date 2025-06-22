# India Population Visualization Dashboard

This Streamlit app provides an interactive dashboard for visualizing population and demographic parameters across Indian states and districts. Users can select primary and secondary parameters to compare, and view results on an interactive map.

## Features

- Select any Indian state or view overall India
- Choose primary and secondary parameters for visualization
- Interactive map with bubble size and color representing selected parameters
- Hover over districts for detailed information

## Tech Stack

- Python
- Streamlit
- Pandas
- Plotly

## Getting Started

1. **Install dependencies:**

   ```sh
   pip install streamlit pandas plotly
   ```

2. **Prepare your data:**

   Ensure `india.csv` is present in the same directory as [`app.py`](app.py). The CSV should include columns: `State`, `District`, `Latitude`, `Longitude`, and demographic columns.

3. **Run the app:**

   ```sh
   streamlit run app.py
   ```

## File Structure

- [`data_scrap/carte/app.py`](app.py): Main Streamlit application
- `india.csv`: Dataset containing state, district, latitude, longitude, and demographic data

---

*Developed for interactive visualization of Indian population and demographic