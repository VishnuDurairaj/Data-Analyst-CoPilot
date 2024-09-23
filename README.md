# **Data Analyst Copilot**

## **Project Overview**
**Data Analyst Copilot** is an AI-powered assistant designed to help users perform end-to-end data analysis through a conversational chat interface. Users can upload an Excel file, and the AI assistant will assist with all aspects of data analysis, from pre-processing to advanced model building. The code is executed in a separate Jupyter environment, providing a flexible and interactive experience for data exploration and analysis.

### **Key Features**
- **Seamless Excel File Upload**: Users can upload an Excel file to kickstart the analysis.
- **Conversational Interaction**: Through chat-based conversation, users can ask the assistant to perform various tasks related to data analysis.
- **Data Pre-processing**: Handle missing data, perform data cleaning, feature scaling, encoding, and more.
- **Data Visualization**: Generate charts, graphs, and other visualizations to better understand the data.
- **Exploratory Data Analysis (EDA)**: Perform descriptive statistics, correlation analysis, and identify patterns in the data.
- **Model Building**: Build machine learning models such as regression, classification, and clustering models.
- **Jupyter Environment**: The code for data analysis runs in a separate Jupyter environment, providing full flexibility and transparency.
- **Customizable Code Execution**: Users can access and modify code during the analysis process.

### **How It Works**
1. **Upload Your Data**: Start by uploading an Excel file through the interface.
2. **Conversational Interface**: Interact with the AI assistant through natural language commands. You can ask it to clean the data, visualize it, or build models.
3. **Analysis Pipeline**: The AI assistant will guide you through each step of the analysis pipeline, allowing you to customize operations or adjust the process as needed.
4. **Receive Visual Feedback**: View visualizations and model results in real-time, generated directly in the chat.
5. **Access and Modify Code**: Get access to the underlying code running in the Jupyter environment, allowing you to tweak, optimize, or customize it.

### **Example Commands**
- “Can you clean the missing values in the dataset?”
- “Plot a histogram of the ‘age’ column.”
- “Build a linear regression model to predict sales.”
- “Show a correlation matrix for the dataset.”
- “Can you perform one-hot encoding on categorical variables?”

### **How to Run the Project**

```bash
git clone https://github.com/yourusername/data-analyst-copilot.git
cd data-analyst-copilot
```

### **1.Clone the Repository:**

```bash
git clone https://github.com/yourusername/data-analyst-copilot.git
cd data-analyst-copilot
```

### **2.Run the Services with Docker Compose:**
```bash
docker-compose up
```

Access the Interface: Open your browser and go to http://localhost:8080 to start interacting with the AI assistant.

Upload Your Data: Upload your Excel file through the interface and start a conversation with the AI assistant to analyze the data.