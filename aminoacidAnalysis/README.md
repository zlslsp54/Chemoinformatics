## Amino Acid Descriptors Analysis

Amino Acid에 존재하는 7개의 descriptors를 features로 사용하여 Amino Acid의 유사도를 비지도 학습으로 clustering하고 이를 실제 물리 화학적 특성과 비교 해본다.

### 1. Data Check

  - Read aminoacids.csv file by pandas. It makes data frame of bunch of series
  - Features check
  - Covariance vs Correlation

### 2. Preprocessing

  - Scale preprocessing
  - Transpose

### 3. PCA

  - What is PCA?
  - Why we use PCA?
  - Explained Variance

### 4. Clustering

  - K-Means

### 5. Result

  - It can be seen that similar amino acids are indeed grouped roughly together, with the charged and polar amino acids in one region (e.g. Arg, Lys, Glu, Asp), the small hydrophobic amino acids forming another group (e.g. Ala, Pro, Val) and the aromatic amino acids in a third region(e.g. Phe, Trp)

end
