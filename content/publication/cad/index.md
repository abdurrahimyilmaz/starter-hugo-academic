---
title: 'Machine Learning Approach on High Risk Treadmill Exercise Test to Predict Obstructive Coronary Artery Disease by using P, QRS, and T waves’ Features'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Abdurrahim Yilmaz
  - Mert Ilker Hayiroglu
  - Serkan Salturk
  - Levent Pay
  - Ali Anil Demircali
  - Cahit Coskun
  - Rahmetullah Varol
  - Ozan Tezen
  - Semih Eren
  - Tugba Cetin
  - Ahmet Ilker Tekkesin
  - Huseyin Uvet

# Author notes (optional)
#author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-10-15T00:00:00Z'
doi: 'https://doi.org/10.1111/myc.13498'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Current Problems in Cardiology*
publication_short: In *Current Problems in Cardiology*

abstract: Introduction- TET results and patients' clinical symptoms influence cardiologists' decision to perform Coronary Angiography (CAG) which is an invasive procedure. Since TET has high false positive rates, it can cause an unnecessary invasive CAG. Our primary objective was to develop a machine learning model capable of optimizing TET performance based on electrocardiography (ECG) waves characteristics and signals. Methods- TET reports from 294 patients who underwent CAG following high risk TET were collected and categorized into those with critical CAD and others. The signal was converted to time series format. A dataset containing the P, QRS, and T wave times and amplitudes was created. Using this dataset, five machine learning algorithms were trained with 5-fold cross validation. All these models were then compared to the performance of cardiologists on V5 signal. Results- The results from five machine learning models were clearly superior to the cardiologists' V5 signal performance (p < 0.0001). In addition, the XGBoost model, with an accuracy of 80.92±6.42% and an area under the curve (AUC) of 0.78±0.06, was the most successful model. Conclusions- Machine learning models can produce high-performance diagnoses using the V5 signal markers only as it does not require any clinical markers obtained from TET reports. This can lead to significant contributions to improving clinical prediction in non-invasive methods

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: ''
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '**Samples**'
  focal_point: 'smart'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---