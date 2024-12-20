# AdamelloGlacier
Assessment of the retreat of the Adamello Glacier using Sentinel-2 Images.


This study focuses on monitoring glacier changes using multispectral satellite data from Sentinel-2. The Adamello Glacier is the largest glacierized area in the Italian Alps and is analyzed to assess glacier retreat and vegetative growth in areas where the glacier has receded. Various spectral indices, including NDWI, NDSI, NDVI, and MSAVI, were computed with GEE to enhance the features of the area. Two classification methods have been performed: one unsupervised, Kmeans, and one supervised, Random Forest using Python notebook. Both methods faces some challenges in divide in clusters the area and distinguishing melting snow from rocks, vegetation and urban areas. To improve classification results, different numbers of clusters were tested. The Random Forest classifier, benefiting from labeled training data, demonstrated higher accuracy and robustness in distinguishing different land cover types. Results indicated a decrease in glacier extent, with a difference in snow and ice coverage of 1, 12 km2 from 2019 to 2022. The spectral indices showed changes in snow and ice cover, with indices values indicating increased melting. These results underscore the importance of using both classification methods and spectral indices to monitor glacier dynamics and highlight the impact of climate change on glacial environments.



To visualise the report download the file at the following link: 📄 https://github.com/Ellenn17/AdamelloGlacier/raw/main/Report_AdamelloRetreat.pdf
