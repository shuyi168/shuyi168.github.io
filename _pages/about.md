---
permalink: /
title: "<span style='font-family: Times New Roman;'>Educational Background</span>"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style="font-family: Times New Roman; text-align: justify;">
Bachelor's Degree: Zhejiang University School of Medicine. GPA(4.61/5), Rank(1/73)<br>
Master's Degree in progress: Vanke School of Public Health, Tsinghua University.
</p>

<span style='font-family: Times New Roman;'>Student work experience</span>
------
**<span style='font-family: Times New Roman;'>Zhejiang University</span>**  
<span style='font-family: Times New Roman;'>1. Secretary of the General Branch of Zhejiang University School of Medicine, Class of 2019</span>  
<span style='font-family: Times New Roman;'>2. Leader of Apricot Grove Art Troupe, Zhejiang University School of Medicine</span>  
<span style='font-family: Times New Roman;'>3. Class President of Preventive Medicine 1901, Zhejiang University School of Medicine</span>  
<span style='font-family: Times New Roman;'>4. Leader of Zhejiang University School of Medicine Summer Practice Group</span>  
<span style='font-family: Times New Roman;'>5. Officer of Zhejiang University Photography Association</span>  
<span style='font-family: Times New Roman;'>6. Member of Zhejiang University Athletic Team</span>  
**<span style='font-family: Times New Roman;'>Tsinghua University</span>**  
<span style='font-family: Times New Roman;'>1. Secretary of the Party Branch of Public Health Master 4, Tsinghua University</span>  
<span style='font-family: Times New Roman;'>2. Captain of Badminton Team, Tsinghua University School of Medicine</span>  

<span style='font-family: Times New Roman;'>Honours and Awards</span>
------
<span style='font-family: Times New Roman;'>1. Zhu Kezhen Scholarship (the highest level scholarship of Zhejiang University)</span>  
<span style='font-family: Times New Roman;'>2. Three times National Scholarship (2019-2020/2020-2021/2022-2023)</span>  
<span style='font-family: Times New Roman;'>3. Four times Zhejiang University First Class Scholarship (2019-2020/2020-2021/2021-2022/2022-2023)</span>  
<span style='font-family: Times New Roman;'>4. Outstanding Graduates of Zhejiang Province</span>  
<span style='font-family: Times New Roman;'>5. Runner-up of Men's 800m in Zhejiang Provincial University Games</span>  
<span style='font-family: Times New Roman;'>6. Top Ten Students of Zhejiang University/Top Ten Students of Zhejiang University School of Medicine</span>  
<span style='font-family: Times New Roman;'>7. Zhejiang University's nine consecutive titles in school athletics</span>  

<span style='font-family: Times New Roman;'>Publications</span>
------
<span style='font-family: Times New Roman;'>1. <b>Jin S</b><sup>#</sup>, Li C<sup>#</sup>, Miao J, et al. Sociodemographic Factors Predict Incident Mild Cognitive Impairment: A Brief Review and Empirical Study. J Am Med Dir Assoc. 2023 Sep 14. [[Pubmed]](https://pubmed.ncbi.nlm.nih.gov/37716705/)</span>  
<span style='font-family: Times New Roman;'>2. <b>Jin S</b><sup>#</sup>, Li C<sup>#</sup>, Cao X, et al. Association of lifestyle with mortality and the mediating role of aging among older adults in China. Arch Gerontol Geriatr. 2022 Jan-Feb.</span>  
<span style='font-family: Times New Roman;'>3. Sun K<sup>#</sup>, <b>Jin S</b><sup>#</sup>, Yang Z, et al. Transition to healthier lifestyle associated with reduced risk of incident dementia and decreased hippocampal atrophy. J Affect Disord. 2024 Jan 7.</span>  
<span style='font-family: Times New Roman;'>4. Li C<sup>#</sup>, <b>Jin S</b><sup>#</sup>, Cao X, et al. Catastrophic health expenditure among Chinese adults living alone with cognitive impairment: findings from the CHARLS. BMC Geriatr. 2022 Aug 4. </span>  
<span style='font-family: Times New Roman;'>5. Liu X<sup>#</sup>, Li C<sup>#</sup>, <b>Jin S</b><sup>#</sup>, et al. Functional disability and receipt of informal care among Chinese adults living alone with cognitive impairment.</span>  

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
