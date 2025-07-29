# CAS_docs
A location to store CAS articles and related documents

## Project overview

CAS uploads several articles annually, each with subarticles and associated documents and figures. This repository serves as a central location for CAS members and volunteers to organize and manage their article uploads

## Repo structure

Each project should be given its own folder underneath [2025_reports](./2025_reports/). Each year, a new primary folder will be made to house corresponding articles for that year. 

### example structure

```plaintext
CAS_DOCS/
├── 2025_reports/
│ ├── policy_memo_demo/
│ │ ├── fig/
│ │ │ ├── S1.PNG
│ │ │ ├── S2.PNG
│ │ │ └── S3.PNG
│ │ ├── src/
│ │ │ └── manuscript.md
│ │ ├── yaml/
│ │ │ └── _manuscript.yaml
│ │ ├── out/
│ │ │ └── [generated PDF files (if using a generator), etc.]
│ │ ├── _markmeld.yaml
│ │ ├── template.xls
│ │ ├── forms.pdf
│ │ ├── peer_review_comments.md
│ ├── another_project/
│ │ ├── fig/
│ │ ├── src/
│ │ ├── yaml/
│ │ └── out/

```

View a [demo](./2025_reports/policy_memo_demo/).

## How to contribute

Clone the repository, upload your folder and begin adding commits!

