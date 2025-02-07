# **Labeled Components Analysis in Earth Science Images**  

## **Overview**  
This project analyzes labeled components in Earth Science images using image processing techniques. It extracts key statistics such as the number of components, their area, and integrated density. The results are visualized through color-labeled components and individual component highlights.  

## **Key Features**  
- **Thresholding**: Converts grayscale images into binary format.  
- **Connected Component Analysis (CCA)**: Identifies and labels connected regions.  
- **Statistical Extraction**: Computes area and integrated density for each component.  
- **Visualization**: Displays labeled components in distinct colors and highlights individual components.  

## **Dataset**  
The project works with various Earth Science images such as:  
- Erosion patterns  
- Metamorphic formations  
- Coral structures  
- Tree images  
- Mineral samples  

## **Technologies Used**  
- **OpenCV**: Image processing and analysis  
- **NumPy**: Numerical computations  
- **Matplotlib**: Visualization of results  
- **Pandas**: Tabular data representation  

## **Installation & Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Labeled-Components-Analysis-Earth-Science.git
   cd Labeled-Components-Analysis-Earth-Science
   ```  
2. Install dependencies:  
   ```bash
   pip install opencv-python numpy matplotlib pandas
   ```  
3. Run the analysis script:  
   ```python
   from analysis_script import analyze_image_components  
   analyze_image_components("path_to_image.jpg")  
   ```  

## **Results & Insights**  
- **Component Count**: Identifies distinct labeled regions in the image.  
- **Quantitative Metrics**: Provides area and integrated density for each component.  
- **Visualization**: Labeled components are color-coded for easy identification.  

## **Applications**  
- **Geological Studies**: Analyzing rock formations, sediment patterns, and mineral compositions.  
- **Environmental Research**: Identifying changes in landforms, soil structures, and vegetation patterns.  
- **Remote Sensing**: Processing satellite imagery for terrain classification and resource mapping.  

## **Conclusion**  
This project demonstrates how image processing can be used to analyze labeled components in Earth Science images. By leveraging connected component analysis and statistical measures, it provides valuable insights into geological and environmental structures.  
