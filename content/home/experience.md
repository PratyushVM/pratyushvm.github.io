---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle: 

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Systems Software Engineer
    company: NVIDIA
    company_url: 'https://www.nvidia.com/en-in/'
    # company_logo: org-gc
    location: Pune, India
    date_start: '2022-07-25'
    date_end: ''
    description: 
        Working as a Systems Software Engineer on CUPTI (Cuda Profiling Tools).

  - title: HPC Intern
    company: KLA-Tencor
    company_url: 'https://www.kla.com/'
    # company_logo: org-x
    location: Chennai, India
    date_start: '2021-12-05'
    date_end: '2022-04-29'
    description: Used CUDA to parallelize and migrate custom algorithms used in defect detection to GPUs. Did profiling with Nsight Compute and Nsight Systems and co-optimization for maximum performance.

  - title: Research Intern
    company: IIT Roorkee
    company_url: 'https://iitr.ac.in/Departments/Computer%20Science%20and%20Engineering%20Department/index.html'
    # company_logo: org-x
    location: Roorkee, India (Remote)
    date_start: '2021-11-05'
    date_end: '2022-06-29'
    description: "
    Guide - [Dr.Debiprasanna Sahoo](https://sites.google.com/view/debiprasannasahoo/home?authuser=0)


    Studied the design and micro-architecture of GPUs, SIMT Cores, Warp schedulers and the SIMT pipeline. Worked on formalizing the working of the SIMT warp scheduler as part of my [Bachelors' Thesis](https://drive.google.com/file/d/1xuq5YXFx3X96e3lvlG8KRdhVVXNxfOiw/view?usp=sharing).
    "

  - title: Research Intern
    company: IISc Bangalore
    company_url: 'https://www.csa.iisc.ac.in/'
    # company_logo: org-x
    location: Bangalore, India (Remote)
    date_start: '2021-05-01'
    date_end: '2021-10-12'
    description: "
    Guide - [Prof.R.Govindarajan](https://www.csa.iisc.ac.in/~govind/index.html)


    - Recipient of the Indian Academy of Sciences’ Summer Research Fellowship SRFP ’21.
    
    - Explored pipeline parallelism and hybrid model-data parallelism in training deep CNNs on multi-GPU setups, using Tensorflow Lingvo and GPipe.
    "

  - title: Research Intern
    company: IIT Madras
    company_url: 'http://www.cse.iitm.ac.in/'
    # company_logo: org-x
    location: Chennai, India (Remote)
    date_start: '2020-03-24'
    date_end: '2020-10-29'
    description: "
    Guide - [Dr.Rupesh Nasre](https://www.cse.iitm.ac.in/~rupesh/?mode=Home)


    Implemented different parallel algorithms to compute maximum network flow on GPUs using CUDA.Also experimented with fundamental graph problems like parallel BFS, parallel Bellman-Ford SSSP on GPUs.
    "

  - title: Winter Intern
    company: HPRCSE Labs, IIITDM Kancheepuram
    company_url: 'http://web.iiitdm.ac.in/noor/index.html'
    # company_logo: org-x
    location: Chennai, India
    date_start: '2019-12-01'
    date_end: '2020-01-31'
    description: "
    Guide - [Dr.Noor Mahammad Sk](http://web.iiitdm.ac.in/noor/index.html)


    Implemented parallel algorithms and explored various tools for code profiling. Also did literature surveys on parallel computing architectures.
    "

design:
  columns: '2'
---
