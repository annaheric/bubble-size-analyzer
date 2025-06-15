# 🫧 Bubble Size Analyzer (Streamlit App)

This Streamlit app allows metallurgists and flotation researchers to analyze bubble size distributions from uploaded froth flotation images.

## 🚀 Features
- 📷 Upload froth images (JPG/PNG)
- 📐 Convert pixel measurements to microns using adjustable scale
- 🎚️ Exclude oversized bubbles with a live max-diameter filter
- 📊 View bubble diameter histogram and stats
- 📥 Download CSV of bubble sizes (µm)

## 🔧 How to Use
1. Open the app in your browser (e.g., https://yourusername-bubble-size-analyzer.streamlit.app)
2. Enter the calibration value (Microns per Pixel)
3. Adjust the "Exclude Bubbles Larger Than (µm)" slider to remove outliers
4. Upload a froth image from flotation circuit
5. View:
   - Annotated bubble detection image
   - Histogram
   - Average diameter
   - Bubble count
6. Click **Download CSV** to export bubble size data

## 📦 Required Dependencies
Automatically installed via `requirements.txt`:
```
streamlit
opencv-python-headless
matplotlib
pandas
pillow
numpy
```

## 📁 Files
- `streamlit_bubble_monitor.py` — Main Streamlit app script
- `requirements.txt` — Python dependencies
- `sample_froth.jpg` — Example test image

## ✅ Deployment Instructions
1. Upload all files to a GitHub repo (public)
2. Go to https://streamlit.io/cloud
3. Click **New App**, connect your GitHub, and point to:
   - Repo: `yourname/bubble-size-analyzer`
   - File: `streamlit_bubble_monitor.py`
4. Click **Deploy**
