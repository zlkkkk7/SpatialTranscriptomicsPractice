# SpatialTranscriptomicsPractice
Load data:

- raw data: too big (21Gb)
- processed data:
    - install package devtools
    
    ```r
    devtools::install_github('satijalab/seurat-data')
    library(SeuratData)
    AvailableData()
    InstallData("stxBrain")
    brain <- LoadData("stxBrain", type = "anterior1")
    ```
    
