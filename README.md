# 🏷 Open Source Data Annotation & Labeling Tools

[![maintained-by-zenml](https://user-images.githubusercontent.com/3348134/173032050-ad923313-f2ce-4583-b27a-afcaa8b355e2.png)](https://github.com/zenml-io/zenml)

At [ZenML](https://github.com/zenml-io/zenml) we believe that annotation and labeling workflows are a core part of
the machine learning lifecycle. As an open-source tool, we wanted to highlight
and recognize the variety of tools that are available to help your workflows
become more data-centric. We had three core criteria to decide whether a
particular tool could make it into the list:

- The tool has an open-source licence.
- The tool is actively maintained.
- The tool is functional and fit for purpose.

We welcome contributions to this list, so if you know of a tool that
we've missed or if you've built one yourself, please do create a PR!

🔥 **Do you use these tools or do you want to add one to your MLOps stack?** At
ZenML, we are looking for design partnerships and collaboration to develop the
integrations and workflows around using annotation within the MLOps lifecycle.
If you'd like to learn more, please [join our
Slack](https://zenml.io/slack-invite/) and leave us a message!

## Contents

- [Multi Modal / Multi Domain](#multi-modal-multi-domain)
- [Text](#text)
- [Images](#images)
- [Audio](#audio)
- [Video](#video)
- [Time Series](#time-series)
- [Other](#other)

# Multi Modal / Multi Domain

| Name | Description | License |
| ---- | ----------- | ------- |
| [Acharya](https://github.com/astutic/Acharya) | A Data Centric MLOps tool for your Named Entity Recognition projects ![](https://img.shields.io/github/stars/astutic/Acharya?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | ? |
| [Adala](https://github.com/HumanSignal/Adala) | An Autonomous Data (Labeling) Agent framework. ![](https://img.shields.io/github/stars/HumanSignal/Adala?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Anudesh](https://github.com/AI4Bharat/Anudesh) | An open source platform to annotate data for Large language models - at scale. ![](https://img.shields.io/github/stars/AI4Bharat/Anudesh?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Classifai](https://github.com/CertifaiAI/classifai) | A comprehensive open-source data annotation platform ![](https://img.shields.io/github/stars/CertifaiAI/classifai?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Computer Vision Annotation Tool (CVAT)](https://github.com/openvinotoolkit/cvat) | A free, online, interactive video and image annotation tool for computer vision ![](https://img.shields.io/github/stars/openvinotoolkit/cvat?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Data Annotator for Machine Learning (DAML)](https://github.com/vmware/data-annotator-for-machine-learning) | An application that helps machine learning teams facilitating the creation and management of annotations ![](https://img.shields.io/github/stars/vmware/data-annotator-for-machine-learning?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [DataGym](https://github.com/datagym-ai/datagym-core) | Open source annotation and labeling tool for image and video assets ![](https://img.shields.io/github/stars/datagym-ai/datagym-core?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Diffgram](https://github.com/diffgram/diffgram) | Training Data (Data Labeling, Annotation, Workflow) for all Data Types (Image, Video, 3D, Text, Geo, Audio, more) at scale ![](https://img.shields.io/github/stars/diffgram/diffgram?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | ELv2 |
| [Hover](https://github.com/phurwicz/hover) | Explore and label on a map of raw data. Handles text, audio and images. ![](https://img.shields.io/github/stars/phurwicz/hover?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Label Studio](https://github.com/heartexlabs/label-studio) | A multi-type data labeling and annotation tool with standardized output format ![](https://img.shields.io/github/stars/heartexlabs/label-studio?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Pigeon](https://github.com/agermanidis/pigeon) | A simple widget that lets you quickly annotate a dataset of unlabeled examples from the comfort of your Jupyter notebook ![](https://img.shields.io/github/stars/agermanidis/pigeon?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [QSL: Quick and Simple Labeler](https://github.com/faustomorales/qsl) | A quick and simple tool for labeling images, videos and time series data, right from Jupyter ![](https://img.shields.io/github/stars/faustomorales/qsl?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Shoonya](https://github.com/AI4Bharat/Shoonya) | Platform to Annotate and label data at scale ![](https://img.shields.io/github/stars/AI4Bharat/Shoonya?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Tator](https://github.com/cvisionai/tator) | Video analytics web platform ![](https://img.shields.io/github/stars/cvisionai/tator?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | AGPL-3 |
| [TornadoAi](https://github.com/slrbl/human-in-the-loop-machine-learning-tool-tornado) | A human-in-the-loop machine learning framework ![](https://img.shields.io/github/stars/slrbl/human-in-the-loop-machine-learning-tool-tornado?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | AGPL-3 |
| [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) | A web/desktop app for editing and annotating images, text, audio, documents and to view and edit any data defined in the extensible .udt.json and .udt.csv standard ![](https://img.shields.io/github/stars/UniversalDataTool/universal-data-tool?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [VGG Image Annotator (VIA)](https://gitlab.com/vgg/via) | A standalone image annotator application packaged as a single HTML file (< 400 KB) that runs on most modern web browsers | BSD-2 |
| [VIAME](https://github.com/VIAME/VIAME) | Video and Image Analytics for Multiple Environments ![](https://img.shields.io/github/stars/VIAME/VIAME?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Custom |
| [Xtreme1](https://github.com/xtreme1-io/xtreme1) | An all-in-one data labeling and annotation platform for multimodal data training and supports 3D LiDAR point cloud, image, and LLM ![](https://img.shields.io/github/stars/xtreme1-io/xtreme1?color=black&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |

# Text

| Name | Description | License |
| ---- | ----------- | ------- |
| [Annotation Lab](https://nlp.johnsnowlabs.com/docs/en/alab/quickstart) | An NLP annotation tool included in `spark-nlp` ![](https://img.shields.io/github/stars/JohnSnowLabs/spark-nlp?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [bulk](https://github.com/koaning/bulk) | Bulk is a quick developer tool to apply some bulk labels ![](https://img.shields.io/github/stars/koaning/bulk?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| MIT | 
| [CoreNLP](https://github.com/stanfordnlp/CoreNLP) | A Java suite of core NLP tools ![](https://img.shields.io/github/stars/stanfordnlp/CoreNLP?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [DataQA](https://github.com/dataqa/nlp-labelling) | Labeling platform for text using weak supervision ![](https://img.shields.io/github/stars/dataqa/nlp-labelling?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [doccano](https://github.com/doccano/doccano) | An open source text annotation tool supporting text classification, sequence labeling and sequence to sequence tasks ![](https://img.shields.io/github/stars/doccano/doccano?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [FLAT - FoLiA Linguistic Annotation Tool](https://github.com/proycon/flat) | A web-based linguistic annotation environment based around the FoLiA format, an XML-based format for linguistic annotation ![](https://img.shields.io/github/stars/proycon/flat?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [INCEpTION](https://github.com/inception-project/inception) | A semantic annotation platform offering intelligent annotation assistance and knowledge management ![](https://img.shields.io/github/stars/inception-project/inception?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [knodle](https://github.com/knodle/knodle) | Knodle (Knowledge-supervised Deep Learning Framework) ![](https://img.shields.io/github/stars/knodle/knodle?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| Apache-2 |
| [Label Sleuth](https://github.com/label-sleuth/label-sleuth) | An open source no-code system for text annotation and building text classifiers ![](https://img.shields.io/github/stars/label-sleuth/label-sleuth?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Markup](https://github.com/samueldobbie/markup) | A web-based document annotation tool, powered by GPT-4 ![](https://img.shields.io/github/stars/samueldobbie/markup?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| Unknown |
| [NER Annotator for Spacy](https://github.com/tecoholic/ner-annotator) | NER Annotator for SpaCy allows you to create training data for creating a custom NER Model with custom tags. ![](https://img.shields.io/github/stars/tecoholic/ner-annotator?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [NPLM](https://github.com/BatsResearch/nplm) | Noisy Partial Label Model(NPLM) ![](https://img.shields.io/github/stars/BatsResearch/nplm?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| N/A |
| [Potato](https://github.com/davidjurgens/potato) | An annotation framework with 20+ templates, editable UI, quality control, data management and an option to add a survey for crowdsourcing ![](https://img.shields.io/github/stars/davidjurgens/potato?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | PolyForm Shield |
| [refinery](https://github.com/code-kern-ai/refinery) | The data scientist's open-source choice to scale, assess and maintain natural language data. ![](https://img.shields.io/github/stars/code-kern-ai/refinery?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Slate](https://github.com/jkkummerfeld/slate) | A Super-Lightweight Annotation Tool for Experts: Label text in a terminal with just Python ![](https://img.shields.io/github/stars/jkkummerfeld/slate?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | ISC |
| [SMART](https://github.com/RTIInternational/SMART) | A tool for building labeled training datasets for supervised machine learning tasks in NLP ![](https://img.shields.io/github/stars/RTIInternational/SMART?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [SpaCy annotator](https://github.com/ieriii/spacy-annotator) | Spacy NER annotator using ipywidgets ![](https://img.shields.io/github/stars/ieriii/spacy-annotator?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | N/A |
| [Small-Text](https://github.com/webis-de/small-text) | Active Learning for Text Classification ![](https://img.shields.io/github/stars/webis-de/small-text?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Snorkel](https://github.com/snorkel-team/snorkel) | Programmatically Build and Manage Training Data ![](https://img.shields.io/github/stars/snorkel-team/snorkel?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [skweak](https://github.com/NorskRegnesentral/skweak) | skweak: Weak supervision for NLP ![](https://img.shields.io/github/stars/NorskRegnesentral/skweak?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| MIT |
| [TALEN](https://github.com/CogComp/talen) | A way to do annotations for NER ![](https://img.shields.io/github/stars/CogComp/talen?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Custom |
| [Theme](https://github.com/Oxid15/theme) | Minimalistic CLI labeling tool for text classification ![](https://img.shields.io/github/stars/Oxid15/theme?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [YEDDA](https://github.com/jiesutd/YEDDA) | A lightweight collaborative text span annotation tool ![](https://img.shields.io/github/stars/jiesutd/YEDDA?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [WeaSEL](https://github.com/autonlab/weasel) | WeaSEL: Weakly Supervised End-to-end Learning ![](https://img.shields.io/github/stars/autonlab/weasel?color=white&label=%E2%AD%90%EF%B8%8F&style=plastic)| Apache-2 |



# Images

| Name | Description | License |
| ---- | ----------- | ------- |
| [3D Slicer](https://www.slicer.org) | Visualization, processing, segmentation, registration, and analysis of medical, biomedical, and other 3D images and meshes ![](https://img.shields.io/github/stars/Slicer/Slicer?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD |
| [Annotate Lab](https://github.com/sumn2u/annotate-lab) | Simplifying Image Annotation ![](https://img.shields.io/github/stars/sumn2u/annotate-lab?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Annotorious](https://github.com/recogito/annotorious) | A JavaScript library for image annotation ![](https://img.shields.io/github/stars/recogito/annotorious?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-3 |
| [AnyLabeling](https://github.com/vietanhdev/anylabeling) | Effortless AI-assisted data labeling with AI support from YOLO, Segment Anything, MobileSAM ![](https://img.shields.io/github/stars/vietanhdev/anylabeling?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [autodistill](https://github.com/autodistill/autodistill) | Images to inference with no labeling (use foundation models to train supervised models) ![](https://img.shields.io/github/stars/autodistill/autodistill?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [bbox-visualizer](https://github.com/shoumikchow/bbox-visualizer) | Make drawing and labeling bounding boxes easy as cake ![](https://img.shields.io/github/stars/shoumikchow/bbox-visualizer?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Bounding Box Editor](https://github.com/mfl28/BoundingBoxEditor) | A JavaFX desktop application for creating image-object-annotations with bounding boxes ![](https://img.shields.io/github/stars/mfl28/BoundingBoxEditor?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [CATMAID](https://github.com/catmaid/CATMAID) | The Collaborative Annotation Toolkit for Massive Amounts of Image Data ![](https://img.shields.io/github/stars/catmaid/CATMAID?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [COCO Annotator](https://github.com/jsbroks/coco-annotator) | A web-based image segmentation tool for object detection, localization, and keypoints ![](https://img.shields.io/github/stars/jsbroks/coco-annotator?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [DeepLabel](https://github.com/jveitchmichaelis/deeplabel) | A cross-platform desktop image annotation tool for machine learning ![](https://img.shields.io/github/stars/jveitchmichaelis/deeplabel?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Etichetta](https://github.com/trikko/etichetta) | A YOLO annotator, for human beings ![](https://img.shields.io/github/stars/trikko/etichetta?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [ilastik](https://github.com/ilastik/ilastik) | Segment, classify, track and count your cells or other experimental data ![](https://img.shields.io/github/stars/ilastik/ilastik?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Custom |
| [ImageTagger](https://github.com/bit-bots/imagetagger) | An open source online platform for collaborative image labeling ![](https://img.shields.io/github/stars/bit-bots/imagetagger?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [imglab](https://github.com/NaturalIntelligence/imglab) | A web based tool to label images for objects that can be used to train dlib or other object detectors ![](https://img.shields.io/github/stars/NaturalIntelligence/imglab?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [KNOSSOS](https://github.com/knossos-project/knossos) | A software tool for the visualization and annotation of 3D image data and was developed for the rapid reconstruction of neural morphology and connectivity ![](https://img.shields.io/github/stars/knossos-project/knossos?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-2 |
| [labelCloud](https://github.com/ch-sa/labelCloud) | A lightweight tool for labeling 3D bounding boxes in point clouds ![](https://img.shields.io/github/stars/ch-sa/labelCloud?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [LabelFlow](https://github.com/labelflow/labelflow) | An open platform for image labeling ![](https://img.shields.io/github/stars/labelflow/labelflow?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Custom |
| [labelme](https://github.com/wkentaro/labelme) | Image Polygonal Annotation with Python (polygon, rectangle, circle, line, point and image-level flag annotation) ![](https://img.shields.io/github/stars/wkentaro/labelme?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Custom |
| [LabelImg](https://github.com/tzutalin/labelImg) | A graphical image annotation tool and label object bounding boxes in images ![](https://img.shields.io/github/stars/tzutalin/labelImg?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [LOST](https://github.com/l3p-cv/lost) | A flexible web-based framework for semi-automatic image annotation ![](https://img.shields.io/github/stars/l3p-cv/lost?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Make Sense](https://github.com/SkalskiP/make-sense) | A free-to-use online tool for labeling photos ![](https://img.shields.io/github/stars/SkalskiP/make-sense?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [MyVision](https://github.com/OvidijusParsiunas/myvision) | Computer vision based ML training data generation tool ![](https://img.shields.io/github/stars/OvidijusParsiunas/myvision?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [OHIF Medical Imaging Viewer](https://github.com/OHIF/Viewers) | OHIF zero-footprint DICOM viewer and oncology specific Lesion Tracker ![](https://img.shields.io/github/stars/OHIF/Viewers?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [OpenLabeler](https://github.com/kinhong/OpenLabeler) | An open source desktop application for annotating objects for AI appplications ![](https://img.shields.io/github/stars/kinhong/OpenLabeler?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Pixano](https://github.com/pixano/pixano-app) | A web-based smart-annotation tool for computer vision applications ![](https://img.shields.io/github/stars/pixano/pixano-app?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | CeCILL-C |
| [Scalabel](https://github.com/scalabel/scalabel) | A web-based visual data annotation tool, supporting both 2D and 3D data labeling ![](https://img.shields.io/github/stars/scalabel/scalabel?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [webKnossos](https://github.com/scalableminds/webknossos) | A fully cloud- and browser-based 3D annotation tool for distributed large-scale data analysis in light- and electron-microscopy based Connectomics ![](https://img.shields.io/github/stars/scalableminds/webknossos?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | AGPL-3 |
| [Yolo_Label](https://github.com/developer0hye/Yolo_Label) | GUI for marking bounded boxes of objects in images for training neural network YOLO ![](https://img.shields.io/github/stars/developer0hye/Yolo_Label?color=purple&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |

# Video

| Name | Description | License |
| ---- | ----------- | ------- |
| [Chitralekha](https://github.com/AI4Bharat/Chitralekha) | An open source video transcreation tool ![](https://img.shields.io/github/stars/AI4Bharat/Chitralekha?color=orange&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [DIVE](https://github.com/Kitware/dive) | Media annotation and analysis tools for web and desktop ![](https://img.shields.io/github/stars/Kitware/dive?color=orange&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [UltimateLabeling](https://github.com/alexandre01/UltimateLabeling) | A multi-purpose Video Labeling GUI in Python with integrated SOTA detector and tracker ![](https://img.shields.io/github/stars/alexandre01/UltimateLabeling?color=orange&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |

# Audio

| Name | Description | License |
| ---- | ----------- | ------- |
| [aubio](https://aubio.org) | A library for audio and music analysis ![](https://img.shields.io/github/stars/aubio/aubio?color=pink&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [audino](https://github.com/midas-research/audino) | Open source audio annotation tool ![](https://img.shields.io/github/stars/midas-research/audino?color=pink&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Praat](https://github.com/praat/praat) | Annotation tool for phonetics analysis ![](https://img.shields.io/github/stars/praat/praat?color=pink&label=%E2%AD%90%EF%B8%8F&style=plastic) | GPL-3 |
| [Peaks.js](https://github.com/bbc/peaks.js) | JavaScript UI component for interacting with audio waveforms ![](https://img.shields.io/github/stars/bbc/peaks.js?color=pink&label=%E2%AD%90%EF%B8%8F&style=plastic) | LGPL-3 |
| [Wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) | Navigable waveform built on Web Audio and Canvas ![](https://img.shields.io/github/stars/katspaugh/wavesurfer.js?color=pink&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-3 |

# Time Series

| Name | Description | License |
| ---- | ----------- | ------- |
| [sktime](https://github.com/sktime/sktime) | A framework for machine learning with time series ![](https://img.shields.io/github/stars/sktime/sktime?color=blue&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-3 |

# Other

| Name | Description | License |
| ---- | ----------- | ------- |
| [Compose](https://github.com/alteryx/compose) | Automated prediction engineering. Allows you to easily structure prediction problems and generate labels for supervised learning ![](https://img.shields.io/github/stars/alteryx/compose?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-3 |
| [Encord Active](https://github.com/encord-team/encord-active/) | Toolkit to test, validate, and evaluate your models and surface, curate, and prioritize the most valuable data for labeling ![](https://img.shields.io/github/stars/encord-team/encord-active?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [Label App](https://github.com/javserjod/label-app) | Application designed to assist in manually editing, visualizing and labelling your moderate-sized datasets ![](https://img.shields.io/github/stars/javserjod/label-app?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |
| [NeuroTrALE](https://github.com/mit-ll/NeuroTrALE-data-manager) | Annotation software for brain mapping, supporting 3D imaging and annotation ![](https://img.shields.io/github/stars/mit-ll/NeuroTrALE-data-manager?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-2 |
| [OpenCRAVAT](https://github.com/KarchinLab/open-cravat) | A modular annotation tool for genomic variants ![](https://img.shields.io/github/stars/KarchinLab/open-cravat?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [PatchSorter](https://github.com/choosehappy/PatchSorter) | An open-source digital pathology tool for histologic object labeling ![](https://img.shields.io/github/stars/choosehappy/PatchSorter?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | BSD-3 |
| [Personal Cancer Genome Reporter (PCGR)](https://github.com/sigven/pcgr) | A stand-alone software package for translation of individual tumor genomes for precision cancer medicine ![](https://img.shields.io/github/stars/sigven/pcgr?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | MIT |
| [Quepid](https://github.com/o19s/quepid) | Gather Human Judgements (aka Explicit Ratings) for Search Quality.  Also a safe space to play with your search algorithm. ![](https://img.shields.io/github/stars/o19s/quepid?color=green&label=%E2%AD%90%EF%B8%8F&style=plastic) | Apache-2 |

# Acknowledgements

Thanks to the creators of
[these](https://github.com/jsbroks/awesome-dataset-tools)
[other](https://github.com/doccano/awesome-annotation-tools)
[repositories](https://github.com/taivop/awesome-data-annotation) (and [this
one](https://github.com/heartexlabs/awesome-data-labeling)!) for getting us
going down the path of creating our own. I used these efforts to get started in
my survey of the space before adding, updating and pruning as per the
open-source and other criteria specified above.
