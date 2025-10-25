# **Restaurant-Review-NER**

**Project Description**

A domain-specific Named Entity Recognition (NER) model built using SpaCy to extract restaurant-specific entities from customer reviews. This model identifies key aspects that customers mention in their feedback, enabling data-driven insights for restaurant business improvement.

**Objective**:

Create a custom NER model that goes beyond generic entity recognition to identify restaurant-specific concepts like food quality, service, ambience, and pricing from unstructured review text.

**Custom Entity Labels**

The model is trained to recognize 6 restaurant-specific entity types:Entity LabelDescriptionExampleRESTAURANTSpecific restaurant names"Olive Garden", "The French Laundry"RESTAURANT_TYPESCuisine types or restaurant categories"Italian", "sushi bar", "fast food"QUALITYFood quality descriptors"delicious", "fresh", "bland", "excellent"SERVICEService-related mentions"friendly staff", "slow service", "attentive"AMBIENCEAtmosphere and environment"cozy", "romantic", "noisy", "elegant"PRICEPrice and value mentions"affordable", "overpriced", "good value"📊 Dataset

**Source**: Restaurant_Reviews.tsv (1000 reviews)

**Sample Size**: 500 reviews selected for annotation

Format: Tab-separated values with Review text and Liked (0/1) columns

Manual Annotation ProcessAnnotation Tool

We used  https://northeastern.instructure.com/courses/228751/assignments/2786113?module_item_id=12233830#:~:text=https%3A//tecoholic.github,an%20external%20site. for manual annotation of the dataset.

**Steps for Creating Annotations:**

Data Preparation:

    -Extracted 500 sample reviews from the dataset
    
    -Converted to text format for annotation

Annotation Process:

    -Uploaded text data to the annotation tool
    
    -Defined 6 custom entity types
    
    -Manually labeled text spans with appropriate entity types
    
    -Exported annotations in JSON format
