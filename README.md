# ops

[Project/ops nexus](http://github.com/robfatland/ops) &#X00E7;e (includes [streets](https://web6.seattle.gov/travelers/), [tides](http://www.dairiki.org/tides/daily.php/ert) and [Oncorhynchus](http://github.com/robfatland/flyingbosun)).


## projects

* ***Geoscience***
  * [pangeo outreach education and training (POETs)](https://github.com/pangeo-data/education-material)
    * also [Pangeo](http://pangeo.io)
    * also the NASA [Common Metadata Repository (CMR)](https://github.com/pangeo-data/cmr)
    * also [pangeo binder](http://binder.pangeo.io)
    * also [pangeo Jupyter Hub](https://nasa.pangeo.io)
    * also Sebastian's Terraform work
    * also [jupyter-earth](https://github.com/pangeo-data/jupyter-earth)
    * also [my work using GOLIVE](https://github.com/robfatland/golive)
      * also [rpy](https://github.com/robfatland/rpy), a little supportive work for the GOLIVE project
  * [Regional Cabled Array notebooks](https://github.com/cormorack/notebooks)
    * for reference: [RCA](http://app-dev.ooica.net) and [Interactive Oceans](https://interactiveoceans.washington.edu)
    * also [synoptic](https://github.com/robfatland/synoptic)
    * also [cormorack](https://github.com/robfatland/cormorack)
    * also [chlorophyll](https://github.com/robfatland/chlorophyll)
    * also [notebooks](https://github.com/robfatland/notebooks)
    * also [galleryclone](https://github.com/robfatland/galleryclone)
    * also find where I put jupyter-ocean, reboot that, update it here
    * also S & D's work, find, update here
    * also [a cormorack-organization version of the notebook gallery](http://github.com/cormorack/gallery) 
    * also artifact work on [whalebooks](http://github.com/cormorack/whalebooks) (more below)
  * [megaptera](http://github.com/whaledr/whalebooks) Making whales -- specifically humpbacks -- accessible via broadband hydrophone
    * also [the megaptera *game*](http://megaptera.swipesforscience.org/#/) 
    * also [bio-acoustic transfer learning (batl)](https://github.com/pshivraj/batl)
* ***Medicine***
  * [aggregate material on secure digital research environments](https://github.com/robfatland/uwsdre) 
    * repo 'sce' should be folded into here ^
    * repo 'cloudsecurity' (for CB) also ^
* ***Data science, with emphasis on using the public cloud***
  * Lightweight data systems; we abbreviate with [Zero2API](https://github.com/robfatland/Zero2API)
  * A cost notification Lambda function called [costnotify](https://github.com/robfatland/costnotify)
  * [Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
  * [Apache Spark](https://spark.apache.org/documentation.html) 
    * Described at ([Wikipedia](https://en.wikipedia.org/wiki/Apache_Spark))
    * Also alternatives must arise, such as [BlazingSQL](https://docs.blazingdb.com)
  * [Transfer Learning (CNN)](https://github.com/pshivraj/batl)
  * [Cloud 101 / 102 work circa 2019](https://github.com/robfatland/cloud101102)
  * [Article of interest](https://hai.stanford.edu/news/the_intertwined_quest_for_understanding_biological_intelligence_and_creating_artificial_intelligence/)
* ***Outreach***
  * [PythonBytes, a middle-school coding club](https://github.com/robfatland/pythonbytes)
  * [The Other Math Club](https://github.com/robfatland/othermathclub)
  * [A little bit of chemistry](https://github.com/robfatland/chemistry) including a binder launch button
  * [A snarky start on some number theory](https://github.com/robfatland/boojum)
  * 
  


## ancillary

Other orgs to review: Goehackweek, cloudmaven, pangeo, haciendata, cormorack, whaledr, research2cloud, escience-pangeo, and cloudbank-project


This should go into POETs repo: 


* [make a Python environment self-configurable...](http://github.com/robfatland/ops)
  * Can use `environment.yml` or `requirements.txt`
    * The latter is associated with `pip install` and can be made a sub-component of the former
    * `environment.yml` as follows
      * `conda env export` produces `environment.yml`
    * `requirements.txt` as follows
      * Create a virtual environment `python3 -m venv /path/to/new/virtual/env`
      * Install packages using `pip install <package>`
      * Save all packages `pip freeze > requirements.txt`
      * "Pin all the package versions"... not sure what the action is or what this means
      * Move `requirements.txt` to the root directory of the project

* [Dog Aging Project](http://dogagingproject.com/)

factor in: 


* old website stuff is out there somewhere


* SEAMONSTER stuff is out there somewhere


* Narwhal stuff is out there somehwere


* [High Mountain Asia](http://himat.org/) and 
[our ++](https://cloudmaven.github.io/documentation/ccs_high_mountain_asia.html)


* [Data8 / Jupyter classrooms](http://data8.org/), also [Zero2JHub](https://zero-to-jupyterhub.readthedocs.io/en/latest/)


* [Amazon Web Services](http://aws.amazon.com) + [SageMaker](https://aws.amazon.com/sagemaker/) + 
[open data](https://registry.opendata.aws/)
* [Google Cloud Platform](http://cloud.google.com) + 
[colab](https://colab.research.google.com/) +
[GEE](https://earthengine.google.com)
* [Microsoft Azure](http://azure.microsoft.com) + 
[ML Studio](https://studio.azureml.net) +
[AI for Earth](https://www.microsoft.com/en-us/ai/ai-for-earth)
* [NVIDIA RAPIDS](https://rapids.ai/)
* [IBM Cloud](https://www.ibm.com/cloud)
