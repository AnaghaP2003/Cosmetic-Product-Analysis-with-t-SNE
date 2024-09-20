# Cosmetic-Product-Analysis-with-t-SNE

Project Description:

This project aims to analyze cosmetic products based on their ingredient compositions using a dataset of various moisturizers. By applying the t-SNE dimensionality reduction technique, we visualize high-dimensional ingredient data in a 2D scatter plot, allowing users to explore relationships and similarities between different cosmetic items. The visualization includes interactive features that display detailed information about each product, such as its name, brand, price, and rank when hovered over.

What the Project Does?

- Data Import and Preprocessing: The project begins by importing a dataset of cosmetic products, filtering for specific types (moisturizers), and preparing the data for analysis.
- Ingredient Tokenization: It tokenizes the ingredient lists, creating a bag-of-words representation to understand ingredient distribution.
- Dimensionality Reduction: The project uses t-SNE to reduce the high-dimensional ingredient data to two dimensions, making it easier to visualize and analyze.
- Interactive Visualization: A scatter plot is created using Bokeh, where each point represents a cosmetic item. Users can hover over points to see detailed information about each product.
  
Why the Project is Useful?

This project provides valuable insights into cosmetic products by enabling users to:

- Identify similarities between products based on ingredient composition.
- Explore and compare different moisturizers without requiring a chemistry background.
- Make informed decisions when selecting cosmetics based on their ingredients.

How Users Can Get Started with the Project?

- Clone the Repository: Download or clone the project repository to your local machine to access the code and dataset.
- Install Required Libraries: Ensure you have the necessary Python libraries installed, such as pandas, numpy, scikit-learn, and bokeh.
- Run the Jupyter Notebook: Open the provided Jupyter Notebook, execute the cells sequentially, and explore the visualizations to analyze the similarities between cosmetic products.
