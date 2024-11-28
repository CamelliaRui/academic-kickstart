+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

"""

[[experience]]
  title = "Research Assistant"
  company = "University of Southern California"
  company_url = "https://chianglab.usc.edu/"
  location = "Los Angeles, California"
  date_start = "2020-06-18"
  description = """*  Helping with a research project on admixture mapping
*  Running simulations of admixed populations using Msprime, pySlim and SLiM"""

[[experience]]
  title = "Research Assistant"
  company = "University of Southern California"
  company_url = "https://chianglab.usc.edu/"
  location = "Los Angeles, California"
  date_start = "2020-05-18"
  description = """*	 Building Pipeline for researching on imputation quality over 50+ populations all over the world for Genome Wide Association Study
*   Skills include using Python, R, Plink, and high performance computing in Linux system
*   Mentoring two undergraduate students in the lab, providing hands-on experience on the research project
*   Awarded Provost Research Fellowship in Fall 2020 and presented research progress during undergraduate poster session"""

[[experience]]
  title = "Research Assistant"
  company = "University of Southern California"
  company_url = ""
  location = "Los Angeles"
  date_start = "2024-03-01"
  date_end = "Present"
  description = """
  Responsibilities include:
  
* Helped developing a machine learning method PerturbVI that discovered gene regulatory networks with
CRISPR perturbation data and single-cell RNA-seq data using Variational Inference and Jax in a
team of three
* Simulated model misspecification of latent variables using Python and improved 6.5% sensitivity
compared to existing methods
* Enabled ultra-fast inference speed with an average convergence time of 70x faster on the largest scale
perturbation matrix (310,385 x 8563) than the existing method

  """
[[experience]]
  title = "Research Assistant"
  company = "University of Southern California"
  company_url = ""
  location = "Los Angeles"
  date_start = "2022-08-01"
  date_end = "Present"
  description = """
  Responsibilities include:
  
* Developed a machine learning method SCFM that identifies gene-to-disease associations on the
largest-scale single-cell RNA-seq data (4.1GB), utilizing coordinate ascent variational inference
* Achieved an average of 32% improvement in sensitivity and discovered an average of 15% more genetic
variants when benchmarking against the existing method through extensive simulations
* Built a new Python package implementing SCFM framework with Jax to achieve ultra-fast computing
speed with an average inference time 15x faster than the existing method (1.3s vs 20s)
* Enabled robustness on calibration and model misspecification over 4000+ simulation scenarios and
benchmarked the method against baseline and other published models
* Accepted as the first-author abstract to a top-tier conference American Society of Human Genetics

"""

+++
