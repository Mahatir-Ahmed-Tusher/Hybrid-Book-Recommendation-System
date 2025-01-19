# Hybrid Book Recommendation System

This project presents a **Hybrid Book Recommendation System** that combines **Cosine Similarity** and **Singular Value Decomposition (SVD)** to deliver personalized and highly accurate book recommendations. It addresses key challenges like data sparsity and scalability, making it a robust solution for modern recommendation systems.



![image](https://github.com/user-attachments/assets/9467b2f7-d3bf-4df9-a47a-e1b7d14cc882)
Figure: Comprehensive architecture of the proposed book recommendation system.

---

## Key Features
- **Hybrid Approach**: Combines content-based filtering (Cosine Similarity) with collaborative filtering (SVD).
- **Precision and Recall**: Achieves a precision score of 0.80 and recall of 0.60, outperforming state-of-the-art methods.
- **Scalability**: Handles large datasets efficiently.
- **User-Centric**: Tailors recommendations based on user preferences and book attributes.
- **Evaluation Metrics**: Employs RMSE, MAE, NMAE, precision, and recall for performance analysis.
  ![Figure 7 Recommended Books for User 2313 in the Top 10](https://github.com/user-attachments/assets/00462686-0d0b-4d89-bdbb-09d283041e72)
  Figure:Recommended Books for User 2313 in the Top 10.


---

## Dataset
The datasets used include:
1. **Books.csv**: Contains book metadata (ISBN, title, author, publisher, etc.).
2. **Ratings.csv**: Includes user ratings for books.
3. **Users.csv**: Contains anonymized user demographics (age, location).

Access the dataset [here](https://drive.google.com/drive/folders/1VrH-B0wU2n--99MsPCCY7OkZPB5Syf1T?usp=sharing).

---

## Results
The hybrid model outperforms traditional recommendation techniques:
- **MAE**: 0.6747
- **RMSE**: 0.5035
- **Precision at K**: 0.80
- **Recall at K**: 0.60

The system demonstrated significant accuracy and reliability in generating book recommendations compared to earlier models.
![image](https://github.com/user-attachments/assets/a7293836-8e10-432d-9b55-16c6298675b2)


---

## Why It’s Better
- **Data Sparsity**: SVD effectively estimates missing values, overcoming sparse data challenges.
- **Customizability**: Adapts to both user preferences and item similarity, enhancing personalization.
- **Benchmarking**: Outperforms several state-of-the-art methods in metrics like MAE, RMSE, and precision.
![image](https://github.com/user-attachments/assets/9e33b7e3-04f0-474c-99e1-d3bcdc4d025a)
Demonstration of Matrix Factorization in Recommendation Systems
---

## Dependencies
To run the project, ensure the following libraries are installed:
- **Python 3.8+**
- **NumPy**
- **pandas**
- **scikit-learn**
- **scikit-surprise**
- **matplotlib**
- **seaborn**

Install dependencies using:
```bash
pip install numpy pandas scikit-learn scikit-surprise matplotlib seaborn
```
## How to Run the Code
1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_name>
```
2. Download and place the dataset files in the data directory.
3. Open the Jupyter Notebook (Book_Recommendation_system.ipynb) and run all cells to train the model and generate recommendations.

## Collaborators
1. Mahatir Ahmed Tusher (Conceptualization, Model building, Methodology, Writing)
2. Saket Choudary Kongara (Validation, Review Editing)
3. Gangavarapu Sreeram (Validation, Review Editing)
4. Srinivas Arukonda (Formal Analysis, Supervision)
5. Sheikha Farook Batha (Visualization)

## Citation
If you use this code or dataset, please cite:
```bash
Tusher, M. A., Kongara, S. C., Sreeram, G., Arukonda, S., & Batha, S. F. Algorithmic Exploration in Reading Behavior Analysis and Recommendations Using Machine Learning. Preprint submitted to Elsevier.
```
## License
This project is licensed under the MIT License.
