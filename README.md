# Minor-Project-1
# groupDNA 🧬📊

`groupDNA` is a Python-based WhatsApp chat analyzer that parses raw text exports to decode group dynamics, track activity trends, and reveal individual communication styles. By processing timestamps, message metadata, and text content, it generates comprehensive behavioral insights and maps out custom communication archetypes.

## 🚀 Features

* **Group Overview & Metrics:** Instantly extracts total messages, active timeline tracking, and individual participation percentages.
* **Custom Activity Heatmap:** Utilizes **NumPy** to map out a 24-hour communication matrix for every participant, displaying text density patterns using customized ASCII density blocks (`.`, `░`, `▒`, `▓`, `█`).
* **Top 10 Words Visualizer:** Cleans the chat data stream using targeted stop-word filtering and punctuation stripping to render a text-based frequency distribution bar chart.
* **Average Response Time Tracker:** Compares sequential messages between different senders to calculate exact average response speeds down to the minute.
* **Personality Archetype Detection:** Implements custom algorithmic logic to profile participants into communication personas based on behavioral thresholds:
    * `Chatterbox` (High message volume)
    * `Night Owl` (Predominant texting between 11 PM – 4 AM)
    * `Message Ninja` (High frequency of deleted messages)
    * `Ghost` (Long stretches of inactive days)
    * `Regular Member` / `Silent Observer`

---

## 🛠️ Tech Stack & Requirements

This project is built strictly using Python 3 and relies heavily on multi-dimensional matrix operations.

* **Python 3.x**
* **NumPy** (For structural heatmap generation and maximum threshold evaluations)
