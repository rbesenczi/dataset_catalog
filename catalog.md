# Comprehensive 3D Medical Imaging Research Dataset Catalogue

**Updated:** 14 November 2026  
**Domains:** Brain/neuroimaging, heart/vascular, dental/maxillofacial, orthopedic/musculoskeletal. **75 dataset entries**, grouped by anatomy; version-specific dataset releases count as entries.  
**Purpose:** Discover research-accessible 3D MRI/CT/CBCT and related imaging datasets; estimate HPC download/storage requirements. Source URLs are linked directly from every dataset name.

**Access keys:** **Open** = public files, still subject to licences; **Terms** = registration, challenge account or data-use terms; **Controlled** = formal research approval/security obligations. **TBD** = no verified single archive size; inspect the release manifest. `~` denotes a reported or approximate value. **Bold** sizes have a specific provider/archive figure associated with the linked source, but may vary by release. Storage generally means **download/distribution size**, not extracted or preprocessed size.

**Scope warning:** Not every item is a native isotropic 3D voxel dataset: some are anisotropic MRI stacks, 3D+t cine imaging, or **3D meshes**. CAMUS is mainly **2D ultrasound** and is retained as a related cardiovascular benchmark.

# I. Brain

## 1. Brain and neuroimaging (44 entries)

### 1.1 Core brain development, lifespan, connectomics and segmentation (20)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [HBCD 2.1](https://www.nbdc-datahub.org/hbcd-release-2-1) | Infant structural, diffusion, functional MRI | 3,605 cohort participants (not all imaged) | TBD; multi-TB possible | Controlled |
| [ABCD 7.1](https://www.nbdc-datahub.org/abcd-release-7-1) | Longitudinal T1/T2, dMRI, resting/task fMRI | 11,860 baseline participants | TBD; potentially tens of TB | Controlled |
| [HCP Young Adult](https://www.humanconnectome.org/study/hcp-young-adult) | 3T/7T structural, diffusion, fMRI | 1,206 S1200 participants | 15.2 TB raw / 63 TB preprocessed / 81.4 TB incl. derivatives (S1200) | Terms |
| [dHCP](https://biomedia.github.io/dHCP-release-notes/) | Neonatal/fetal structural, diffusion, functional MRI | Hundreds; release-dependent | TBD | Research approval |
| [HCP Development](https://www.humanconnectome.org/study/hcp-lifespan-development/data-releases) | Developmental multimodal MRI, ages 5-21 | 652 in Lifespan 2.0 | 22+ TB | Research access |
| [HCP Aging / AABC](https://www.humanconnectome.org/study/hcp-lifespan-aging/data-releases) | Longitudinal aging multimodal MRI | 1,390 imaged; 2,789 sessions, release 2 | 42+ TB | Research access |
| [IXI](https://brain-development.org/ixi-dataset/) | T1/T2/PD/MRA/DTI, registration | ~600 | ~20-27 GB | Open |
| [OASIS-1](https://sites.wustl.edu/oasisbrains/home/oasis-1/) | Structural MRI, aging/dementia | 416 | ~18 GB (estimate) | Open |
| [OASIS-3](https://sites.wustl.edu/oasisbrains/home/oasis-3/) | Longitudinal MRI/PET, neurodegeneration | 1,000+ | TBD | Terms |
| [UK Biobank Brain MRI](https://www.ukbiobank.ac.uk/about-our-data/types-of-data/imaging-data/) | Population-scale brain MRI | ~90k | No download | Controlled |
| [FeTA](https://fetachallenge.github.io/pages/Data_download.html) | 3D fetal T2 MRI, segmentation | 120 training (referenced edition) | ~5 GB (estimate) | Terms |
| [ATLAS R3.0](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html) | T1 MRI, stroke lesion labels | 1,453 | TBD | Terms |
| [CamCAN](https://camcan-archive.mrc-cbu.cam.ac.uk/dataaccess/) | Adult lifespan multimodal MRI | ~650 | TBD | Research approval |
| [ADNI](https://adni.loni.usc.edu/) | Longitudinal MRI/PET, Alzheimer disease | Thousands | Multi-TB possible | Controlled |
| [NKI-Rockland](https://rocklandsample.org) | Structural, diffusion and functional MRI | Hundreds | TBD | Open / terms |
| [UCLA CNP / OpenNeuro ds000030](https://openneuro.org/datasets/ds000030) | Structural/functional MRI, psychiatry | 273 | TBD | Open |


### 1.2 Additional large-scale, developmental and population MRI (8)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [fastMRI Brain](https://fastmri.med.nyu.edu/) | T1/T2/FLAIR raw k-space and reconstructed MRI; accelerated reconstruction | ~6,970 MRI examinations | Multi-TB; modality-dependent | Terms |
| [Calgary-Campinas](https://portal.conp.ca/dataset?id=projects%2Fcalgary-campinas) | 3D T1 MRI, some masks, raw k-space | 526 subjects/files in CONP | **90 GB** on CONP | Open; CC BY-ND |
| [ABIDE I + II](https://fcon_1000.projects.nitrc.org/indi/abide/) | T1 structural MRI + resting fMRI; multi-site autism research | 2,226 datasets combined | TBD | Terms |
| [ADHD-200](https://fcon_1000.projects.nitrc.org/indi/adhd200/) | T1 and resting fMRI; ADHD | 973 datasets | TBD | Terms |
| [COBRE](https://fcon_1000.projects.nitrc.org/indi/retro/cobre.html) | Structural MRI and resting fMRI; schizophrenia | ~146 subjects | TBD | Open / terms |
| [Healthy Brain Network (HBN)](https://healthybrainnetwork.org/) | Pediatric T1/T2, diffusion and functional MRI | Thousands | Multi-TB potential | Terms |
| [PING](https://nda.nih.gov/study.html?id=477) | Structural / diffusion MRI; pediatric neurodevelopment | 1,493 participants; ~1,239 imaged | TBD; use approved manifest | Controlled |
| [PREVENT-AD](https://portal.conp.ca/dataset?id=projects%2Fpreventad-registered) | Longitudinal multimodal MRI, pre-symptomatic Alzheimer disease | 348 | **556 GB** on CONP | Terms / account |

### 1.3 Additional brain tumour MRI (2)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [UPENN-GBM](https://www.cancerimagingarchive.net/collection/upenn-gbm/) | Multiparametric glioblastoma MRI; tumour labels and clinical/genomic information | 630 | **~69 GB NIfTI / ~139.4 GB DICOM** (different distributions) | Open |
| [UCSF-PDGM](https://www.cancerimagingarchive.net/collection/ucsf-pdgm/) | T1/T2/FLAIR, diffusion and perfusion MRI; diffuse glioma labels | 495 patients; 501 examinations | **~142 GB** imaging package | Open |

### 1.4 Additional lesion, segmentation, atlas and vascular MRI (7)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [ISLES 2022](https://zenodo.org/records/7153326) | DWI, ADC, FLAIR; ischemic stroke lesion segmentation | 250 public training cases | **~1.7 GB ZIP** | Open |
| [MSSEG 2016](https://shanoir.irisa.fr/shanoir-ng/welcome) | T1/T2/PD/FLAIR; multiple-sclerosis lesions | ~60 subjects | TBD | Research request |
| [MSSEG-2](https://shanoir.irisa.fr/shanoir-ng/welcome) | Longitudinal FLAIR; new multiple-sclerosis lesions | 100 subjects | ~6 GB reported; verify | Research request / DUA |
| [MRBrainS18](https://mrbrains18.isi.uu.nl/) | T1, T1-IR, FLAIR; tissue/anatomical segmentation | 30 total; 7 labelled training | TBD | Terms |
| [ADAM](https://adam.isi.uu.nl/) | 3D TOF-MRA; intracranial aneurysm detection/segmentation | 113 training subjects | TBD | Terms |
| [Hammers Atlas](https://brain-development.org/brain-atlases/adult-brain-atlases/individual-adult-brain-atlases-new/) | Structural MRI with 95 manually delineated brain labels | 30 subjects | TBD | Academic licence |

### 1.5 Additional longitudinal and clinical MRI (7)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [AOMIC ID1000](https://openneuro.org/datasets/ds003097) | T1, diffusion MRI, movie-watching functional MRI | 928 subjects | TBD; OpenNeuro manifest | Open |
| [AOMIC PIOP1](https://openneuro.org/datasets/ds002785) | T1, diffusion and resting/task fMRI | 216 subjects | TBD | Open |
| [AOMIC PIOP2](https://openneuro.org/datasets/ds002790) | T1, diffusion and resting/task fMRI | 226 subjects | TBD | Open |
| [OASIS-2](https://sites.wustl.edu/oasisbrains/home/oasis-2/) | Longitudinal T1 MRI; aging/dementia | 150 participants; 373 sessions | TBD | Terms |
| [OASIS-4](https://sites.wustl.edu/oasisbrains/home/oasis-4/) | Clinical MRI, cognitive and biomarker information; dementia | 663 subjects; 676 MRI sessions | TBD | Terms |
| [PPMI](https://www.michaeljfox.org/data-resources) | Longitudinal structural/diffusion MRI; Parkinson disease | 1,500+ cohort participants (not all necessarily imaged) | TBD; approved manifest | Controlled / terms |
| [Kirby21](https://www.kennedykrieger.org/kirby-research-center/research/databases) | Multimodal repeated MRI; test-retest reliability | 21 participants | TBD | Open / terms |

**Brain-specific cautions:** The AOMIC ID1000, PIOP1 and PIOP2 studies are distinct collections. OASIS-4 is a separate clinical cohort, not a revised OASIS-3. fastMRI Brain and Calgary-Campinas include raw **k-space** material; that is not interchangeable with reconstructed NIfTI scans. For HBCD, ABCD, PING and PPMI, cohort participant counts are **not** the number of available MRI examinations. See the provider manifest for modality/visit availability.

# II. For MONAI-Geo testing

## 2. Heart and cardiovascular imaging (11 datasets)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/) | Cine cardiac MRI, LV/RV/myocardium | 150 | TBD | Terms |
| [M&Ms](https://www.ub.edu/mnms/) | Multi-vendor cine cardiac MRI | 375 exams | TBD | Terms |
| [CAMUS](https://www.creatis.insa-lyon.fr/Challenge/camus/) | Primarily **2D** cardiac ultrasound, not volumetric 3D | 500 patients | ~2 GB (estimate) | Open / terms |
| [UK Biobank Cardiac MRI](https://www.ukbiobank.ac.uk/about-our-data/types-of-data/imaging-data/) | Population-scale cine cardiac MRI | Tens of thousands | No download | Controlled |
| [MM-WHS](https://zmiclab.github.io/zxh/0/mmwhs/data.html) | Whole-heart CT/MRI, chambers/vessels | 120 total; 40 labelled training | TBD | Terms |
| [ImageCAS](https://github.com/XiaoweiXu/ImageCAS-A-Large-Scale-Dataset-and-Benchmark-for-Coronary-Artery-Segmentation-based-on-CT) | Coronary CTA, artery segmentation | 1,000 | ~89.1 GB (catalogue estimate) | Open |
| [ASOCA](https://asoca.grand-challenge.org/) | Coronary CTA, artery segmentation | 40 public labelled | TBD | Terms |
| [EMIDEC](https://emidec.com/dataset) | Late-gadolinium MRI, infarct segmentation | 100 labelled | TBD | Terms |
| [ImageTBAD (catalogue)](https://github.com/gfahrni/open-cardiovasc-imaging-datasets) | CTA, type B aortic dissection | 100 | ~13.4 GB (catalogue estimate) | Public / verify host |
| [ImageALCAPA (catalogue)](https://github.com/gfahrni/open-cardiovasc-imaging-datasets) | CTA, anomalous coronary artery | 30 | ~2.6 GB (catalogue estimate) | Public / verify host |

## 3. Dental and maxillofacial imaging (7 datasets)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [ToothFairy](https://toothfairy.grand-challenge.org/) | CBCT, inferior alveolar canal | 443; 153 densely annotated | ~30 GB (unverified estimate) | Terms |
| [ToothFairy2](https://toothfairy2.grand-challenge.org/dataset/) | 3D CBCT, 42 segmentation classes | 480 public + 50 hidden test | TBD | Terms / non-commercial |
| [ToothFairy3](https://toothfairy3.grand-challenge.org/dataset/) | 3D CBCT, 77 segmentation classes | 532 public | TBD | Terms / non-commercial |
| [STS-3D-Tooth](https://zenodo.org/records/10597292) | CBCT, semi-supervised tooth segmentation | 371 volumes in [3D mirror](https://huggingface.co/datasets/MedOtter/STS-3D-Tooth); 32 labelled | 31 GB mirror / 31.8 GB full Zenodo record | Open |
| [3DTeethSeg / Teeth3DS+](https://crns-smartvision.github.io/teeth3ds/) | **3D surface meshes**, tooth segmentation | ~1,800 jaw scans | TBD | Dataset terms |
| [3DTeethLand](https://zenodo.org/records/10991302) | **3D surface meshes**, dental landmarks | Subset of Teeth3DS+ | TBD | Dataset terms |

## 4. Orthopedic and musculoskeletal imaging (13 datasets)

| Dataset | Imaging / use | Cases | Download storage | Access |
|---|---|---:|---|---|
| [VerSe 2019/2020](https://verse2020.grand-challenge.org/) | Spine CT, vertebra segmentation | ~374 across editions | ~25 GB (estimate) | Open / terms |
| [SPIDER](https://zenodo.org/records/10159290) | Lumbar spine MRI, discs/vertebrae/canal | 218 patients; 447 series | 3.8 GB | Open |
| [TotalSegmentator CT v1](https://zenodo.org/records/6802614) | CT, 104 structures incl. 59 bones | 1,204 | 28.4 GB | Open |
| [TotalSegmentator CT v2.0.1](https://zenodo.org/records/10047292) | CT, 117 anatomical structures | 1,228 | 23.6 GB | Open |
| [TotalSegmentator CT v3](https://zenodo.org/records/22688904) | CT, 117 structures, improved skeletal labels | 1,939 | 37.4 GB | Open |
| [TotalSegmentator MRI v3](https://zenodo.org/records/22688334) | MRI, 50 anatomical structures | 1,296 | 15.2 GB | Open |
| [AutoImplant](https://autoimplant.grand-challenge.org/) | Skull CT, defect/implant reconstruction | ~200 | ~10 GB (estimate) | Terms |
| [SKM-TEA](https://aimi.stanford.edu/datasets/skm-tea-knee-mri) | Knee qDESS MRI, k-space, cartilage/menisci | 155 | 900 GB compressed / 1.6 TB expanded | Terms |
| [fastMRI Knee](https://fastmri.med.nyu.edu/) | Knee MRI raw k-space and DICOM | ~1,500 raw MRI exams | 1.35 TB k-space + 164 GB DICOM (original release) | Terms |
| [Osteoarthritis Initiative (OAI)](https://nda.nih.gov/oai) | Longitudinal knee MRI, osteoarthritis | 4,796 participants | Multi-TB possible | Controlled / terms |
| [CTSpine1K](https://github.com/MIRACLE-Center/CTSpine1K) | Spine CT, vertebra segmentation | 1,005 | ~150 GB raw NIfTI (varies) | Open / terms |
| [CTPelvic1K](https://zenodo.org/records/4588403) | Pelvic CT, sacrum/hips/lumbar spine | 1,184 across 7 sources | ~17 GB Zenodo subsets/labels; full raw data distributed across sources | Open / mixed terms |
| [RibFrac](https://ribfrac.grand-challenge.org/) | Chest CT, rib fracture segmentation | 660 | TBD | Terms |
