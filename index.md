
[Publications](./_pages/publications.html) || [Tools/Software](./_pages/tools.html) || [Notes](./_pages/notes.html)

Please check out [About](./_pages/aboutme.html) to see my bio and personal research history.


### My research interests

AI Alignment - Formal methods for AI - Causality - [NeuroAI](https://xcorr.files.wordpress.com/2022/12/neuroai-big-tent-page-1.png) 


<!--  I enjoy working on "edge cases". In science and engineering, we easily get carried away with the success/prediction rates of our models and how "well" they perform. But, oftentimes, our models do poorly at trivial(?) tasks and we do not exactly know why. Most likely explanation is due to the naive assumptions we had to make for the sake of simplicity or computational complexity. -->

I have genuine interest in corner cases where our models don't function as expected. Instead of ignoring such cases, I try to find out why they don't work - which would shed light on why they did work at first place.

> "What do scientists and painters have in common? They both tend to fall in love with their models" <br> (heard at KLI summer school, 2017, Venice)


I am interested in developing tools for fault tracing via causality concerning the fundamental problems in AI alignment. To enable safety in AI systems, I believe, there is an urgent need for developing novel methods to verify the system functioning with certain formal guarantees.


### Research topics I am also interested (aka. sidetracked by):
Mathematical physics of (space)time, Information Geometry, Neuromorphic computing...


<!-- **To be specific**: 

My research interests revolve around concerns related to AI Alignment in safety-critical systems.

I am particularly interested in AI safety risks that emerge as a result of flawed system design choices. Such issues can arise from (i) selecting the incorrect objective function, (ii) selecting a difficult/expensive to evaluate objective function, and/or (iii) undesirable behavior exacerbated by the training procedure (e.g. distribution shifts) [[1](https://arxiv.org/pdf/2401.10899)]. I intend to concentrate on the robustness failures from the problem of (iii). However, the listed problems are intertwined since potential solutions for (iii) imply a solution to (i) where the correctness guarantees of the objective function should not be impeded by the computing time and evaluation problem of (ii). An objective function designates the ends in AI system design, but it can be misleading because, in practice, it is often an incomplete specification [[2](https://drive.google.com/uc?export=download&id=1k93292JCoIHU0h6xVO3qmeRwLyOSlS4o)]. Even if the system satisfy the given (incomplete) specification, the means are also important because the system may have discovered undesirable loopholes to solve the task (namely, reward hacking/reward corruption/specification gaming) [[2](https://drive.google.com/uc?export=download&id=1k93292JCoIHU0h6xVO3qmeRwLyOSlS4o)] [[3](https://arxiv.org/pdf/1711.09883)] [[4](https://arxiv.org/pdf/1705.08417)]. Furthermore, even with the correct specifications, undesirable behaviors may still emerge due to corner cases, as different conditions may trigger the systems to find unsafe workarounds to complete the tasks. Existing techniques for improving robustness mostly rely on Gaussian statistics and i.i.d. assumptions, making them unsuitable for a wide range of distribution families. As a result, the verification techniques to be developed should be able to perform model checking in a variety of distributions and, possibly, partially observable scenarios. Developing a novel logic-based formalism specifically for AI verification enhanced with causal reasoning would be one way to approach the aforementioned issues. Causality combined with the probabilistic model checking framework [[5](https://arxiv.org/pdf/2105.09108)] can be used to characterize the different types of distribution shifts and their effects on system behavior. The new framework would require special focus on working assumptions such as causal sufficiency (‘no unobserved confounding’).

The main purpose of the tools to be developed is to building up the theoretical infrastructure for a flexible formal verification method to cope with potential loopholes in any kind of sequential decision-making process which are broadly implemented in AI systems. The future research on the presented questions concerning the theory of AI may invoke the development of new methods that would have direct practical applications in the field. I am most curious about the application areas of autonomous driving, robotics and control, and neuroAI. Due to the immediate impacts on the human-life, these applications particularly highlight the need for theoretically-supported and safe AI engineering practice.

-->



<!---
All this should be 
commented out

## Reading list/ notes/ sources:
- Bulleted
- List


## Projects:

- Bulleted
- List


## Publications:
- Bulleted
- List



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/basakkcgl/whoisbasak/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/basakkcgl/whoisbasak/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

-->
