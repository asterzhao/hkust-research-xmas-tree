# HKUST Research Christmas Tree 2024

This Christmas tree visualization is built using bibliometric records of over 5,500 HKUST publications from the Scopus database in 2024. The tree highlights the most frequently used “Index Keywords”, showcasing key research areas and achievements of the year. 

Read this blog article to learn more: https://library.hkust.edu.hk/sc/where-hkust-research-meets-christmas-cheer

<img src="https://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2024/12/christmas_tree_wordcloud_highres_indexkeywords.png" alt="HKUST Research Christmas Tree 2024" width="400">

## **Technical Details**

The word cloud was generated using Python with the following steps:

1. **Data Preparation**:
   - Bibliometric records were extracted from the Scopus database and saved into a CSV file (replace with your own file name).
   - The “Index Keywords” column from the dataset was preprocessed to remove stop words.

2. **Word Cloud Creation**:
   - A custom mask image of a Christmas tree (`christmas_tree.png`) was used to shape the word cloud.
   - The color palette includes festive red, green, and gold tones, applied using a custom color function.

3. **Visualization**:
   - The word cloud was generated using the `WordCloud` library and displayed with `Matplotlib`.
   - Final outputs were saved as high-resolution images for sharing and display.



## **Credits**

- **Data Source**: Scopus bibliometric records of HKUST publications in 2024.
- **Libraries Used**: 
  - [NumPy](https://numpy.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [Pillow](https://pillow.readthedocs.io/)
  - [WordCloud](https://github.com/amueller/word_cloud)
  - [Matplotlib](https://matplotlib.org/)
- This README file was drafted by ChatGPT-4o-latest with human editing. 


## **License**

This project is available for non-commercial use. Feel free to adapt and share with proper attribution to Aster Zhao, HKUST Library. 
