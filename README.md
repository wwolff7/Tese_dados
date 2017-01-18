# Regionalização hidrológica do Estado de Santa Catarina: uma abordagem sazonal e geoestatística baseada em modelos 

## Modelo de regionalização de vazãoes de Santa Catarina
 
  * RVSC [http://52.67.209.248/rvsc/index.php] (http://52.67.209.248/rvsc/index.php)

## Dados disponibilizados

### Pastas das séries de vazão
  - **Brutos**: dados brutos de vazão diária das estaçes fluviométricas, divididos pelas principais bacias do Estado de Santa Catarina (Macrobacias);
  - **Preenchido**: dados preenchidos de vazão diária das estações fluviométricas divididos para cada Macrobacia;
  - **Bacias**: arquivos de saída do plugin `r.basin` do sistema de informação geográfica GRASS GIS, contendo diferentes variáveis oriundas da caracterização morfométrica das bacias de drenagem das estaçes fluviométricas, classificadas pelos códigos fornecidos pela Agência Nacional das Águas.
  
### Pastas de arquivos texto
  - **Pluvi**: arquivo `Pluvi.csv` organizado para análise da precitação média anual (Coluna ANUAL), média sazonal de verão (Coluna DJF), média sazonal de outono (Coluna MAM), média sazonal de inverno (Coluna JJA) e média sazonal de primavera (Coluna SON);
  - **Param**: arquivos organizados para análise dos parâmetros das curvas de permanência de vazão (CPVs). Parâmetros das CPVs para período total - `ParamANO.csv`; parâmetros das CPVs para período sazonal de verão - `ParamDJF.csv`; parâmetros das CPVs para período sazonal de outono - `ParamMAM.csv`; parâmetros das CPVs para período sazonal de inverno - `ParamJJA.csv`; parâmetros das CPVs para período sazonal de primavera - `ParamSON.csv`.      

### Pastas de dados geográficos
  - **Raster**: pasta contendo os arquivos rasters oriundos da interpolação espacial da precipitação média anual e sazonal, bem como dos parâmetros das curvas de permanência de vazão (CPVs) total e sazonal. Precipitação média anual - `PluviANO.tiff`; precipitação média sazonal de verão, outono, inverno e primavera - `PluviDJF.tiff`, `PluviMAM.tiff`, `PluviJJA.tiff`, `PluviSON.tiff`, respectivamente. Parâmetros de escala (média) e forma (desvio padrão) das CPVs para período total - `MuANO.tiff` e `SigmaANO.tiff`. Parâmetros de escala (média) e forma (desvio padrão) das CPVs para período sazonal de verão, outono, inverno e primavera - `MuDJF.tiff` e `SigmaDJF.tiff`, `MuMAM.tiff` e `SigmaMAM.tiff`,`MuJJA.tiff` e `SigmaJJA.tiff`, `MuSON.tiff` e `SigmaSON.tiff`, respectivamente;
  - **Shape**: pasta contendo os aquivos shapefile utilizados. 
