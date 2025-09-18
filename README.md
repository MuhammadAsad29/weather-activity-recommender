# 🌦️ Weather Activity Recommender

**Short description:**
☀️🌧️ Weather Activity Recommender — Suggests activities and recommendations based on real-time or user-provided weather conditions.

## 📖 Detailed Description

This project implements a **Weather-Based Activity Recommender** that suggests suitable activities and recommendations
depending on the current or user-input weather condition. Instead of just showing raw weather data, the system applies
conditional logic to map weather states (sunny, rainy, cloudy, cold, hot, etc.) to meaningful recommendations.

✨ **Features:**

- Lightweight, rule-based recommender (no datasets required).
- Handles different weather conditions such as sunny, rainy, cloudy, stormy, and snowy.
- Provides contextual activity suggestions (e.g., "Go for a walk" on sunny days, "Stay in and read a book" on rainy days).
- Easily extendable — more activities, tips, or API-based real-time weather can be added.
- Runs directly in Jupyter Notebook, making it beginner-friendly and educational.

🔧 **Tech stack:**

- Python 3.8+
- ipywidgets (for interactivity, if enabled)
- Jupyter Notebook

🚀 **Use cases:**

- A fun project to demonstrate conditional logic in Python.
- Teaching students about simple recommender systems.
- Can be extended into a real-world app by integrating live weather APIs.

This project is intentionally simple and lightweight, making it a perfect starting point for learning how to
design recommendation systems without datasets or complex ML models.

## 📂 Project Structure

- `weather_based_activity_recommender.ipynb` — Main Jupyter Notebook implementing the recommender logic.

## ⚡ How It Works

1. User selects or provides a weather condition (sunny, rainy, cloudy, snowy, etc.).
2. The system uses conditional logic to map that condition to a set of predefined activities.
3. Outputs activity suggestions along with a contextual message.

## ✅ Example Mapping

```python
if weather == "sunny":
    print("Great day for a walk or outdoor sports!")
elif weather == "rainy":
    print("Perfect time to read a book or enjoy a hot drink indoors.")
elif weather == "snowy":
    print("Stay warm! Maybe build a snowman or enjoy hot chocolate.")
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/MuhammadAsad29/weather-activity-recommender.git
cd weather-activity-recommender
```

2. Launch Jupyter Notebook and open `weather_based_activity_recommender.ipynb`:

```bash
jupyter notebook weather_based_activity_recommender.ipynb
```

3. Run all cells and test the recommender with different weather inputs.

## 🔮 Future Improvements

- Integrate a live weather API (like OpenWeatherMap).
- Add GUI/Gradio app for easier interaction.
- Expand activity suggestions with categories (indoor, outdoor, solo, group, etc.).

---

**Author:** Muhammad Asad
