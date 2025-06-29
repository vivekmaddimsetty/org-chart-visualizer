# org-chart-visualizer

# 📊 Visualization Dashboard for Organizational Hierarchies

A lightweight, interactive dashboard to **visualize organizational hierarchies** using uploaded spreadsheets (CSV from Google Sheets or LibreOffice). This tool automatically parses **Manager–Employee relationships** and displays a **tree-style graph** of the org structure.

## 🚀 Features

- 📤 Upload any `.csv` file with `Manager` and `Employee` columns
- 🧠 Automatically detects relationships and builds a hierarchy
- 🖼️ Visualizes the hierarchy using interactive **graph plots**
- ✅ Validates input and handles basic errors
- 🔒 No external server needed—runs locally in a browser

## 📁 Input Format

Upload a `.csv` file with the following format:

```csv
Employee,Manager
Alice,Bob
Bob,Carol
Carol,CEO
David,Bob
Eve,Carol
```

## 🛠️ Tech Stack

- **Frontend/UI**: [Streamlit](https://streamlit.io/)
- **Data Handling**: [Pandas](https://pandas.pydata.org/)
- **Graph Visualization**: [NetworkX](https://networkx.org/), [Matplotlib](https://matplotlib.org/)

## 🧪 Getting Started

### 1. Clone the Repository

```bash
git clone https://code.swecha.org/your-group/visualization-dashboard.git
cd visualization-dashboard
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install streamlit pandas networkx matplotlib
```

### 3. Run the App

```bash
streamlit run app.py
```

### 4. Use the App
- Open the link shown (usually `http://localhost:8501`)
- Upload your `.csv` file
- View the interactive org chart

## 🧩 File Structure

```
├── app.py                   # Main Streamlit app
├── example.csv              # Sample input file
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
```

## 👥 Team & Contributions

| Name             | Contributions                          |
|------------------|-----------------------------------------|
| Vivek Maddimsetty | Dashboard UI, CSV Parsing, Streamlit Integration |
| Jeevan           | LibreOffice compatibility, Test data handling |
| Nikshay          | Role hierarchy logic, visualization improvements |

## 📌 To-Do / Future Features

- [ ] Tree-style collapsible org chart (e.g., with D3.js)
- [ ] Export to PNG/PDF
- [ ] Role renaming/editing in UI
- [ ] Multi-org support in one graph
- [ ] Google Sheets API integration

## 📬 Contact

Maintained by the team at **Swecha Internship Group**

- Vivek Maddimsetty – [GitLab](https://code.swecha.org/vivekmaddimsetty) | [Instagram](https://instagram.com/vivek_maddimsetty)
- Jeevan – [GitLab](https://code.swecha.org/jeevan)
- Nikshay – [GitLab](https://code.swecha.org/nikshay)

