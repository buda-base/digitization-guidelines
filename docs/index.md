Introduction

This is the latest version of the Digitization Guidelines for the BUDA project.

    The definition of good data int for false 
    dsdsfsdf

dsssd

    Definition of good data

```
Definition of good data
```
| Feature | Standard | 
| ------------ | ------------- | 
| Format | *archive images:* JPEG 2000 (**.j2k**); <br>*web images:* TIFF G4 (**.tif**) for text, JPEG (**.jpg**) for color images | 
| Resolution | 600 dpi/ppi | 
| Size | *archive images:* > 5 MB; *web images:* > 400 KB | 
| Bits | 24-bits |
| Compression | uncompressed, highest data size |
| Dimensions | consistent width and height |
| Image quality | clean image without: <br> • border<br> • scan line<br> • flare<br> • double page<br> • missing text
| Organization | accession number / archive / volume / images |
| Metadata | duly completed *Biblio Info Sheet* |

**数字化工作流程 Digitization Workflow**

Starting from July 2017, the workflow is divided into 5 broad processes:

1. **Finding Opportunities** - The DPE looks for acquisition opportunities.

2. **Selection and Digitization** - The DPE identifies potential acquisitions, confirms it ;is needed by 1) consulting the mobile app, 2) consulting the FR. He then digitizes them, does the QC1 (1st Quality Control) and submits the images to the FR.

3. **Quality Control and Processing** - The FR does the QC2 (2nd Quality Control), post-processes them, to then submits the Access Files (web images) with a metada report to the DPM.

4. **Quality Assurance** - The DPM performs a QA (Quality Assurance) assessment, submits the files to the DAM and confirms that the DPE can be paid for the work.

5. **Archiving and Publishing** - The DAM reviews the Access files,  catalogued by the librarians publishes them. The librarians can now create metadata such as structural or semantic outlines. Every quarter, the DPM collects Master Files (archive images) and submits them to the DAM for archival.

从2017年7月开始,工作流程分为5大流程:

1. **寻找机会** - 首先DPE或者有时FR寻找获取扫描机会。

2. **选择和数字化**——DPE使用移动应用检查，审核可获取的扫描资料，通过后数字化它们,然后进行QC1(1质量控制)并提交图片给FR。

3. **质量控制和处理** - FR进行QC2(第2质量控制)，发现问题时进行处理,然后将文档(网络图片文档)和元数据发送给DPM。

4. **质量保证** - DPM执行QA(质量保证)评估,然后提交文档给DAM并确认可以支付DPE。

5. **存档和发布**——DAM浏览文档,然后由图书管理员编目，由DAM发布。之后，图书管理员创建元数据,如目录和提纲。每个季度,DPM收集原始图片文档(存档图片)并提交给DAM存档。

s

    The Python-Markdown documentation provides a [list of extensions][exts]
    which are available out-of-the-box. For a list of configuration options
    available for a given extension, see the documentation for that extension.



    You may also install and use various [third party extensions][3rd]. Consult
    the documentation for provided by those extensions for installation instructions
    and available configuration options. data int definition



| Old Variable Name | New Variable Name or Expression        |
| ----------------- | -------------------------------------- |
| current_page      | page                                   |
| include_nav       | nav&#124;length&gt;1                   |
| include_next_prev | (page.next_page or page.previous_page) |
| site_name         | config.site_name                       |
| site_author       | config.site_author                     |
| page_description  | config.site_description                |
| repo_url          | config.repo_url                        |
| repo_name         | config.repo_name                       |
| site_url          | config.site_url                        |
| copyright         | config.copyright                       |
| google_analytics  | config.google_analytics                |
| homepage_url      | nav.homepage.url                       |
| favicon           | {{ base_url }}/img/favicon.ico         |