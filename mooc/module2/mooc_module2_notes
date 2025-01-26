# Module 2

## Computational Documents

- Reduce errors in programming, data transformations, statistical procedures
- Ensure calculation traceability
- Help bridge the gap between public and behind the scenes

### Problems Preventing Reproducibility and Leading to Errors

1. **Lack of Information**
   - Data not correctly explained, kept secret, experimental protocol type, decisions, hypotheses -> overall transparency
   - Notebooks are essential here

2. **Unrestrained Use of Computers Leading to Errors**
   - Example: Excel with macros for statistics & data processing
   - Reliance on proprietary software limits transparency, traceability

3. **Lack of Strictness and Organization**
   - Backup loss, lack of version control, lack of software engineering practices such as code review and CI

4. **Cultural/Sociological Barriers**
   - Some prioritize simplicity over rigor -> leave details out (which can be essential)
   - Some fear being exposed or their work being reused/stolen -> lowers will to be transparent

### Best Practices for Transparency and Reproducibility

1. Open Formats (e.g., Markdown, org-mode, CSV) for reliability & portability
2. Open Software (R/Python) for flexibility and inspectability
3. Avoid Proprietary Platforms for easier data replication across different locations
4. Use Version Control Systems for tracking and collaboration
5. Encourage Collaboration to increase recognition and ensure proper credit

### Principles

1. **Purpose**
   - Ensure transparency by combining explanations, code, and results into one reproducible document

2. **Process**
   - Track analysis from raw data to final visualization
   - Use Open Formats
   - Execute code fragments inline and export results

### Features

- Code fragments interact
- Customize code/result visibility in final document
- Computational Documents are flexible:
  - Jupyter supports multiple languages
  - Org-mode supports good multi-language integration

## Hands-On

### Jupyter

Jupyter documents have two types of cells: **code cells** and **markdown cells**

#### Features

- Run code blocks, keep variable states, restart kernel
- Keyboard shortcuts
- Autocomplete
- Integrates with other languages such as R via magic commands (e.g., `%%R`, `%%sh`)
- Allows sharing via VCS
- Allows export to HTML, PDF, LaTeX
- Visibility control with hide code option

### RStudio

RStudio documents use R Markdown to mix code and markdown.

- Similar to Jupyter: Executes code in console, displaying results below, persistent data, keyboard shortcuts
- Allows section folding for easier navigation in large documents
- Allows exporting to HTML, PDF, Word with the "Knit" function
- Visibility control with `echo = FALSE`
- Supports integrations with other languages (no persistence for Python variables)

### Org-mode

Lightweight markup language in Emacs

- Code block execution (R, Python, etc.)
- Retains variable states in sessions
- Supports multiple languages in one document
- Allows export to HTML, PDF, LaTeX
- Visibility control of sections and blocks with tags (e.g., `:noexport:`)
- Control over document layout and style

## Collaboration

- **Co-authors**: Different levels of enthusiasm & tech expertise
  - For enthusiastic ones: Ensure tools work on all OS
  - For benevolent ones: Handle coding and exports; allow them to edit markdown content
  - For resistant ones: Use computational docs for results and graphics and share separate documents for collaboration

## Sharing

- **Temporary**: RPubs
- **Permanent**: GitHub, GitLab
- **Archive tools**: Zenodo, Figshare, Hal, etc.

### Best for the Job

- **Jupyter**: Best for lessons, tutorials. User-friendly and dynamic.
- **RStudio**: Best for articles, papers. Integrates perfectly with R.
- **Org-mode**: Best for advanced, hardcore users. Powerful navigation, multi-language support, etc.

#### Cons for Jupyter

- JSON format is hard to read without tools. RStudio and Org-mode use rich text formats that are readable.
- Limited support for article preparation compared to the other two.

### Helpful Links for Preparing Docs for Journals/Conferences

- [Ultimate IPython Notebook](http://blog.juliusschulz.de/blog/ultimate-ipython-notebook)
- [Hide Code Plugin](https://github.com/kirbs-/hide_code)
- [R Markdown Manuscript](http://svmiller.com/blog/2016/02/svm-r-markdown-manuscript/)
- [Kleinberg Grid Simulator Example](https://github.com/balouf/Kleinberg/blob/master/KleinbergsGridSimulator.ipynb)

### Important for Reporting

- [MOOC Reporting Link](https://lms.fun-mooc.fr/courses/course-v1:inria+41016+self-paced/courseware/66bc811404b8481da5f794de54681c5e/ca6911afc7154c699007475bf818071d/)