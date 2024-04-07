# DeepBioNet_dataset_BCCD_WBC_Classifition
Customized Dataset


**Deep Bio-Net Dataset**

Dataset Description:

    Dimension: 640 × 480px
    Resolution: 96dpi
    Subtypes: RBCs, WBCs, Platelets

Dataset Splits:

    DTrain:
        Subtypes: RBCs, WBCs, Platelets
        Size: 2000
    DTest:
        Subtypes: RBCs, WBCs, Platelets
        Size: 100
    DVal:
        Subtypes: RBCs, WBCs, Platelets
        Size: 80

**WBC Dataset**

Dataset Description:

    Dimension: 640 × 480px
    Resolution: 96dpi
    Subtypes: Neutrophil, Lymphocyte, Monocyte, Eosinophil

Dataset Splits:

    DTrain:
        Neutrophil: 2000
        Lymphocyte: 2206
        Monocyte: 1920
        Eosinophil: 1859
    DTest:
        Neutrophil: 536
        Lymphocyte: 597
        Monocyte: 518
        Eosinophil: 505
    DVal:
        Neutrophil: 286
        Lymphocyte: 257
        Monocyte: 270
        Eosinophil: 264

Dataset Collection Procedure:

    Image Capturing:
        Microscopic examination using Olympus BX53 microscope (4× to 100× magnification)
        Image acquisition with white filter light source and 100× objective lens
        EP50 camera with 0.5× ex-focus factor captured high-resolution images (12,344 × 12,344 pixels) stored in TIFF format

    Preprocessing and Blood Cells Annotation:
        Resizing to 640 × 480 pixels in JPEG format
        Annotation using graphical annotation tool, saved in XML format (PASCAL VOC standard)
        Integration of subset of WBC dataset images with BCCD dataset
