# File Structure

Following is the tree of files in this repo, please check the notes for each file to have the understanding of how the purposes of each file.
```text
.
├── _config.yml (config file for the website, contact maintainer for editing)
├── _includes (website structure, contact maintainer for editing)
│   ├── footer.html
│   └── header.html
├── _layouts (website structure, contact maintainer for editing)
│   └── default.html
├── .gitignore (git ignore, contact maintainer for editing)
├── archive (archive webpages, please have new folders within for different workshops)
│   ├── 2024-jan (a workshop archive directory)
│   │   ├── index.html (webpage)
│   │   └── xxx.png (and single-use resources)
│   ├── 2024-oct
│   │   └── index.html
│   └── 2025-jul
│       └── index.html
├── assets (reusable resources directory)
│   ├── banner-large.jpg
│   ├── banner.jpg
│   ├── favicon.png
│   └── main.css (website structure, contact maintainer for editing)
├── editor-handbook.md (this file)
├── index.html (homepage directory)
├── LICENSE (do not edit)
├── program (program directory)
│   └── index.html (webpage)
├── README.md (repo README)
├── registration (registration directory)
│   └── index.html (webpage)
├── sitemap.xml (sitemap file for SEO, contact maintainer for editing)
└── venue (venue directory)
    └── index.html (webpage)
```

# Principles of Editing

Please place resuable resources in ```./assets```, and single-use resources in the related directory.

# How to Edit

As the webpages for the website are explicitly seperated into different directories, 
editors just need to edit the corresponding file within the dedicated directory.
For example, if the editor would like to edit program webpage, then the file needs to be amended 
is ```./program/index.html```.

Meanwhile, please check with maintainer if anything related to structure needs to be amended.

The website is still in construction, thus the layout might be imperfect, we are continously working on this to provide a better version.