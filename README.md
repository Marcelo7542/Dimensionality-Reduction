English Description Below


Análise de Redução de Dimensionalidade e Classificação

Este repositório apresenta a implementação de técnicas avançadas de redução de dimensionalidade e 
classificação supervisionada utilizando as bibliotecas de machine learning em Python, como scikit-learn, numpy e matplotlib.

Estrutura do Repositório

PCA (Principal Component Analysis): 

Explora a redução de dimensionalidade utilizando PCA tradicional e incremental, além de análise com memmap para grandes datasets.

Random-Projection-LLE: 

Implementação de projeções randômicas e LLE (Locally Linear Embedding).

T-SNE-and-others: 

Exploração de algoritmos como t-SNE para visualização e comparação com outras técnicas.

Técnicas Utilizadas

Principal Component Analysis (PCA):
  
  Projeção de dados 4D em 2D e 3D para visualização de dados multidimensionais.
  
  Comparação entre PCA manual, completo e IncrementalPCA para cenários com restrição de memória.
  
  Otimização de componentes para preservar variância e minimizar erro de reconstrução.

Random Projection e LLE:

  Projeção Randômica:
  
  Comparei Gaussian Random Projection, Sparse Random Projection e Johnson-Lindenstrauss.
  
  Apropriado para grandes datasets devido à sua eficiência computacional.
  
  Locally Linear Embedding (LLE):
  
  Redução de dimensionalidade baseada em aprendizado de representações locais, projetando dados para dimensões menores enquanto preserva estruturas não-lineares.
  
  Implementado com visualização em 2D e integração em pipelines para Random Forest.
  


t-SNE e Outros:

  Comparando visualização e avaliação de classificações usando Random Forest padrão

  t-SNE: 
  
  Redução de dimensionalidade para 2D, aplicada ao dataset MNIST, focando na visualização eficiente de padrões locais em dados de alta dimensão.
  
  
  Isomap: 
  
  Método que preserva distâncias geodésicas em dados com estruturas não-lineares, utilizado em conjunto com Random Forest para avaliação de classificações baseadas em representações reduzidas.
  
  
  LDA (Linear Discriminant Analysis): 
  
  Técnica supervisionada que maximiza a separação entre classes e facilita a visualização em dimensões reduzidas.
  
  
  MDS (Multidimensional Scaling): 
  
  Mantém distâncias pairwise ao reduzir dimensões, usado como abordagem alternativa para visualizações compactas de dados grandes.










Dimensionality Reduction and Classification Analysis

This repository showcases the implementation of advanced dimensionality reduction and supervised classification techniques using Python machine learning libraries 
such as scikit-learn, numpy, and matplotlib.

Repository Structure

PCA (Principal Component Analysis):

Explores dimensionality reduction using traditional and incremental PCA, as well as memmap analysis for large datasets.

Random-Projection-LLE:

Implements random projections and Locally Linear Embedding (LLE).

T-SNE-and-others:

Explores algorithms like t-SNE for visualization and comparison with other techniques.
Techniques Used

Principal Component Analysis (PCA):

  Projects 4D data into 2D and 3D for visualizing multidimensional data.
  
  Compares manual PCA, full PCA, and IncrementalPCA for memory-constrained scenarios.
  
  Optimizes components to preserve variance and minimize reconstruction error.

Random Projection and LLE:

  Random Projection:
  
  I used Gaussian Random Projection, Sparse Random Projection and Johnson-Lindenstrauss.
  Suitable for large datasets due to its computational efficiency.
  
  Locally Linear Embedding (LLE):
  
  A dimensionality reduction method based on learning local representations, projecting data into lower dimensions while preserving non-linear structures.
  Includes 2D visualization and integration in pipelines with Random Forest.

t-SNE and Others:
  Comparing visualization and evaluation using standard Random Forest
  t-SNE:
  
  Reduces dimensionality to 2D, applied to the MNIST dataset, focusing on efficient visualization of local patterns in high-dimensional data.
  
  Isomap:
  
  Preserves geodesic distances in data with non-linear structures, used alongside Random Forest to evaluate classifications on reduced representations.
  
  LDA (Linear Discriminant Analysis):  
  
  A supervised technique that maximizes class separation and facilitates visualization in reduced dimensions.
  
  MDS (Multidimensional Scaling):
  
  Maintains pairwise distances while reducing dimensions, serving as an alternative approach for compact visualizations of large datasets.
    
