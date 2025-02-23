# 🚀 Movie Recommendation System  

## 📌 Project Overview  
This project is a **content-based movie recommendation system** that suggests movies based on user input. It uses **TF-IDF vectorization** and **SBERT embeddings** to compute similarity between user preferences and movie descriptions.

## 📂 Project Structure  
📁 Movie-Recommendation-System
│── 📄 Main_file.csv # Dataset containing movie details

│── 📜 requirements.txt # Required Python libraries

│── 📓 Movie_Recommendation.ipynb # Jupyter Notebook with implementation

|── 📓 Movie_Recommendation.pdf  # Jupyter Notebook converted to pdf

│── 📝 README.md # Project documentation

## 📊 Dataset Details  
- The dataset **(Main_file.csv)** contains movie titles, genres, descriptions etc.  
- It is used to train the recommendation system.
- I have collected random data from these links, which provide datasets related to different movie genres.
- You can explore the datasets by following the links to see details like movie titles, ratings, release years, etc., for each genre.
  | No. | Genre      | Link                                                                 |
|-----|------------|-----------------------------------------------------------------------|
| 1   | Action     | [action.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/action.csv) |
| 2   | Animation  | [animation.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/animation.csv) |
| 3   | Biography  | [biography.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/biography.csv) |
| 4   | Comedy     | [comedy.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/comedy.csv) |
| 5   | Crime      | [crime.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/crime.csv) |
| 6   | Family     | [family.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/family.csv) |
| 7   | Horror     | [horror.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/horror.csv) |
| 8   | Romance    | [romance.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/romance.csv) |
| 9   | Sci-Fi     | [sci-fi.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/sci-fi.csv) |
| 10  | Adventure  | [adventure.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/adventure.csv) |
| 11  | Drama      | [drama.csv](https://raw.githubusercontent.com/Simatwa/movies-dataset/main/data/drama.csv) |


## 🔧 Setup Instructions

### 1 **Download the Dataset**  
Ensure you have the dataset file in the correct location. For example, download the file and save it as `"F:/Main_file.csv"`.

---

### 2 **Open and Execute the Jupyter Notebook**  
1. Open Jupyter Notebook on your system by typing the following command in your terminal:

    ```bash
    jupyter notebook
    ```

2. Once the notebook opens in your browser, navigate to the location of the Jupyter notebook file you are working on.

3. Open the Jupyter notebook file.

4. **Execute the Code**: Run the code cells one by one in sequence by pressing `Shift + Enter`.
   
5. I have mentioned all the required installing in jupyter notebook for your reference also refer `requirement.txt` for necessay libaries you can run below code.

   `!pip install pandas scikit-learn sentence-transformers matplotlib Pillow requests`

6. When you execute the list, it will give you example prompts based on the genre or data provided. You can either use the prompts generated from the list or enter your own custom prompt and press Enter to get the results.

---

### 3 **Follow the Instructions in the Notebook**  
- Ensure to correctly reference the file location in your code like so: `"F:/Main_file.csv"` or
- If you prefer different location to place the file please change the location with full path in jupyter nodebook Step 1.
- The code should execute sequentially without issues, and you can see the results/output as you proceed through each step.

---

## 4 *Salary Expectation $25 to $35 / Hour* 

### ✅ **You're All Set!**  



