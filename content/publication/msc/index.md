+++
title = "Automotive 3D Object Detection Without Target Domain Annotations"
date = 2018-06-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fredrik K. Gustafsson", "Erik Linder-Norén"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "Master of Science Thesis in Electrical Engineering, Linköping University"
publication_short = "Master of Science Thesis in Electrical Engineering, Linköping University"

# Abstract and optional shortened version.
abstract = "In this thesis we study a perception problem in the context of autonomous driving. Specifically, we study the computer vision problem of 3D object detection, in which objects should be detected from various sensor data and their position in the 3D world should be estimated. We also study the application of Generative Adversarial Networks in domain adaptation techniques, aiming to improve the 3D object detection model's ability to transfer between different domains. The state-of-the-art Frustum-PointNet architecture for LiDAR-based 3D object detection was implemented and found to closely match its reported performance when trained and evaluated on the KITTI dataset. The architecture was also found to transfer reasonably well from the synthetic SYN dataset to KITTI, and is thus believed to be usable in a semi-automatic 3D bounding box annotation process. The Frustum-PointNet architecture was also extended to explicitly utilize image features, which surprisingly degraded its detection performance. Furthermore, an image-only 3D object detection model was designed and implemented, which was found to compare quite favourably with current state-of-the-art in terms of detection performance. Additionally, the PixelDA approach was adopted and successfully applied to the MNIST to MNIST-M domain adaptation problem, which validated the idea that unsupervised domain adaptation using Generative Adversarial Networks can improve the performance of a task network for a dataset lacking ground truth annotations. Surprisingly, the approach did however not significantly improve upon the performance of the image-based 3D object detection models when trained on the SYN dataset and evaluated on KITTI."

abstract_short = "In this thesis we study a perception problem in the context of autonomous driving. Specifically, we study the computer vision problem of 3D object detection, in which objects should be detected from various sensor data and their position in the 3D world should be estimated. We also study the application of Generative Adversarial Networks in domain adaptation techniques, aiming to improve the 3D object detection model's ability to transfer between different domains."

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-148585"
url_preprint = ""
url_code = "https://github.com/fregu856/3DOD_thesis"
url_dataset = ""
url_project = ""
url_video = "https://youtu.be/KdrHLXpYYlg"
url_slides = "http://www.fregu856.com/static/msc_thesis_slides.pdf"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = []

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
