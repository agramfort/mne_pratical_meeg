# Material for Practical MEEG workshop using the MNE Software

More info on the workshop: [http://practicalmeeg2019.org/](http://practicalmeeg2019.org/)

Authors:

	- Alexandre Gramfort, Inria, CEA Neurospin
	- Denis A. Engemann, Inria, CEA Neurospin

You will need to [download data](https://owncloud.icm-institute.org/index.php/s/cNu5jmiOhe7Yuoz/download)

You will need also to have installed MNE-Python on your machine.
See instructions at: https://mne.tools/stable/install/mne_python.html

### Schedule

Before you arrive if you do not know any Python I invite you to read these tutorials:
[intro Python](0a-Intro_Python.ipynb), [intro Numpy](0b-Intro_Numpy.ipynb).

#### Day 1 (Tuesday December 3, 2019)

 - 08:30 – 09:00 Registration, with coffee/tea + Welcome & intro
 - 09:00 – 10:30 Lecture 1: Data organization (Robert) and initial data processing(Alex)
 - 10:30 – 12:30 Hands-on: [From raw to ERPs](1-From_raw_to_epochs_evoked_ERF_ERP.ipynb) using MNE

 - 12:30 – 13:30 Lunch

 - 13:30 – 15:00 Lecture 2: Time-Frequency analysis (JM)
 - 15:00 – 17:00 Hands-on 2: [Time-Frequency analysis](2-sensors_time_frequency.ipynb) using MNE
 - 17:00 – 17:30 Wrap-up / Q&A session

#### Day 2 (Wednesday December 4, 2019)

 - 09:00 – 10:30 Lecture 3: Forward modeling and anatomical pipeline (Alex & François)
 - 10:30 – 12:30 Hands-on 3: [Creating head and forward models](3-Forward_model.ipynb) using MNE

 - 12:30 – 13:30 Lunch

 - 13:30 – 15:00 Lecture 4: Source estimation / Inverse problem
 - 15:00 – 17:00 Hands-on 4: [Dipole fitting](4a-Inverse_source_localization_dipole_fit.ipynb), [distributed sources](4b-Inverse_source_localization_mne_dspm.ipynb) and beamformers using MNE
 - 17:00 – 17:30 Wrap-up / Q&A session

#### Day 3 (Thursday December 5, 2019)

 - 09:00 – 10:30 Lecture 5: Group level analysis (Robert)
 - 10:30 – 12:30 Hands-on 5: [Group level analysis](TODO) using MNE

 - 12:30 – 13:30 Lunch

 - 13:30 – 15:00 Lecture 6: Miscellaneous topics
 - 15:00 – 17:00 Hands-on 2: Playground and final try out
 - 17:00 – 17:30 Wrap-up / Q&A session


### Bring your own data

The last session will be mostly dedicated to adressing participants' requests. We encourage
you to prepare some EEG/MEG/ECoG/sEEG data you would be interested in processing with MNE.
If you are coming with colleagues, try to organize small groups with similar interests (1-4 people).

### Cite

The code from this tutorial is heavily inspired from this article:

	Mainak Jas, Eric Larson, Denis Engemann, Jaakko Leppakangas, Samu Taulu, Matti Hamalainen,
	and Alexandre Gramfort. 2018. A Reproducible MEG/EEG Group Study With the MNE Software: 
	Recommendations, Quality Assessments, and Good Practices.
	Frontiers in Neuroscience. 12, doi: 10.3389/fnins.2018.00530

The MNE software when used in publications should be acknowledged using citations.

To cite MNE-C or the inverse imaging implementations provided by the MNE software, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, L. Parkkonen,
	M. Hämäläinen, MNE software for processing MEG and EEG data, NeuroImage, Volume 86,
	1 February 2014, Pages 446-460, ISSN 1053-8119, [DOI]

To cite the MNE-Python package, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, R. Goj, M. Jas,
	T. Brooks, L. Parkkonen, M. Hämäläinen, MEG and EEG data analysis with MNE-Python,
	Frontiers in Neuroscience, Volume 7, 2013, ISSN 1662-453X, [DOI]
