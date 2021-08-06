# Welcome to lightsaber

<!-- For full documentation visit [mkdocs.org](https://www.mkdocs.org). -->

`lightsaber` is designed ground up to provide a _simple_, _composible_, and unified
model training framework. It has been designed based on state-of-the-art open source
tools and extended to support the common use cases for disease progression modeling (DPM). 

`lightsaber` provides four main components:

* Data ingestion modules
* Model Trainers
* DPM problem specific model evaluation
* Model tracking and support for post-hoc model evaluation.

Each of these components are designed such that a user should be able to pick some
or all of the modules and embed these seamlessly with their current workflow. 
Futhermore, when used in the recommended manner, `lightsaber` provides a _batteries included_
approach allowing the modeler to focus only on developing the logic of their model and
letting `lightsaber` handle the rest.

Currently, we support the following DPM use cases:

* classification: one or multi-class
* time-to-event modeling: one or multi-class

Also, we support and extend the following frameworks:

* `scikit-learn` compliant models: for classical models
* `pytorch` compliant models: for general purpose models, including deep learning models.


To summarize, it is thus an `opinionated` take on how DPM should be conducted providing with a 
unified core to abstract and standardize out the engineering, evaluation, model training, and model tracking
to support: **(a) reproducible research, (b) accelarate model development, and (c) standardize model deployment**.

## Installation Instructions

From source: 

* for barebones `lightsaber`: `pip install .` 
* For support with doc: `pip install .[doc]`
* For all: `pip install .[full]`

