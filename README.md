#### Library Main Navigation: &nbsp; &nbsp; <b> [Ecosystem Library Home](https://github.com/NIH-NICHD-Ecosystem) </b> &nbsp; | &nbsp;[User Stories](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/README.md) &nbsp; | &nbsp; [Efforts](https://github.com/NIH-NICHD-Ecosystem/Efforts/blob/main/README.md) &nbsp; | &nbsp; [Library Help](https://github.com/NIH-NICHD-Ecosystem/LibraryHelp/blob/main/README.md)
</br><br/>

# E7: NICHD Data Ecosystem Assessment

<br/> 


### The NICHD Data Ecosystem Assessment provides a comprehensive understanding of how scientific data are shared, governed, and sustained across NICHD-relevant data repositories. It uses a standardized framework to describe high-priority data repositories in support of implementing NIH data sharing policies as well as NICHD- and NIH-wide data strategies.  


<br/>

# Table of Contents
- [Effort Overview](#effort-overview)
- [Effort Documentation](#effort-documentation)
    - [Data Dictionary Development](#data-dictionary-development)
    - [Ecosystem Assessment Variables](#ecosystem-assessment-variables)
    - [Development Approach](#development-approach)
    - [Data Dictionary Development](#data-dictionary-development)
    - [Outcome](#outcome)
    - [How to Use the NICHD Data Ecosystem Assessment Data Dictionary to Conduct Assessments](#how-to-use)
    - [Notes on Use](#notes-on-use)
- [User Stories](#user-stories)

<br/><br/>

# Effort Overview 
The _Eunice Kennedy Shriver_ National Institute of Child Health and Human Development (NICHD) uses and supports a diverse ecosystem of repositories that  share scientific data across maternal, child, and developmental health domains. Systematically assessing these repositories helps NICHD develop strategies to enhance and use these repositories to (1) support NIH data sharing policies and NICHD- and NIH data strategies, (2) foster equitable access and responsible and innovative re-use of shared data, (3) promote trust, transparency, reproducibility, and replicability of NIH-funded research, and (4) meet NICHD and NIH interoperability and sustainability goals while adhering to or strengthening data governance and security requirements. 

This effort is focused on assessing data repositories using  the NICHD Data Ecosystem Assessment Data Dictionary, a standardized set of Ecosystem Assessment Variables (EAVs) used to characterize repository features. 

NICHD Data Ecosystem Assessment results have been used to populate the [NICHD Data Repository Finders](https://github.com/NIH-NICHD-Ecosystem/E1_Data-Repository-Finder/blob/main/README.md), inform requirements for NICHD-funded data repositories, develop recommendations for improving [AI-readiness](https://github.com/NIH-NICHD-Ecosystem/E3_AI-Data-Readiness-Framework/blob/main/README.md) in data repositories, and identify ecosystem gaps based on NICHD research community needs. A syntheses of 25 repository assessments provided actionable opportunities fo r alignment and harmonization of metadata standards, governance practices, access models, and sustainability planning. This is foundational work in NICHD’s development of a diverse, secure, and interoperable data ecosystem.  

#### Details: 
Created by: Eunice Kennedy Shriver National Institute of Child Health and Human Development (NICHD) Office of Data Science and Sharing and MIT Lincoln Laboratory 

NIH Contacts: 

Rebecca Rosen, NICHD ODSS 

Valerie Cotton, NICHD ODSS 

Primary Contact: NICHDecosystem@nih.gov 

<br/><br/>

# Effort Documentation

## Data Dictionary Development
</p> The NICHD Data Ecosystem Assessment Data Dictionary is the primary output of this effort. It defines a standardized set of variables used to describe and assess data repositories across the ecosystem. </p> 

## Ecosystem Assessment Variables
</p> The NICHD Data Ecosystem Assessment Data Dictionary is the primary output of this effort. It defines a standardized set of variables used to describe and assess data repositories across the ecosystem. </p> 

</p> Data Dictionary v1.2 includes 185 Ecosystem Assessment Variables (EAVs) organized into major categories that describe the core characteristics, policies, and functions of a data repository. </p> 

1. **System**: Captures foundational information about the repository itself, including repository identity, descriptions, hosting organization, public web presence, points of contact, Data Repository Finder inclusion criteria, research areas, and core interface features  

2. **Data Submission**: Describes how data are contributed to the repository, including submission eligibility, accepted data types and formats, preparation requirements, metadata requirements, submission agreements, semantic standards, de-identification requirements, submission governance, and data volume limitations  

3. **Data Access**: Describes how users obtain and use data from the repository, including access tiers, access procedures, controlled access processes, data use agreements, de-identification of shared data, , incident handling, re-identification risk mitigation, dataset retraction,  record linkage capabilities, and access fees  

4. **Governance & Security**: Captures the policies, controls, and protections that govern repository operations, including security posture, certifications or authorizations, authentication and authorization mechanisms, and broader controls for protecting data and managing access  

5. **FAIR**: Captures repository features that support Findability, Accessibility, Interoperability, and Reusability, including metadata models, persistent identifiers, provenance, attribution, harmonization, data quality procedures, retention policies, visualization tools, cloud and analysis environments, and programmatic accessibility through APIs or web services  

6. **Usage Statistics**: Describes measures of repository use and impact, including registered and active users, website visits, downloads, submissions, approved access requests, publications citing the repository, usage analytics, workforce contributions, and NIH portfolio indicators related to repository use and submission  

7. **Size of Data**: Captures the scale of repository holdings, including number of datasets, participants or samples represented, total storage size, released data size, growth over time, and storage capacity  

8. **Funding & Costs**: Describes the financial and operational sustainability of the repository, including funding sources, funding duration, sustainability planning, infrastructure maintenance costs, storage and egress costs, cloud compute costs, participation in STRIDES, and cost mitigation strategies  

9. **Core Variables**: To streamline assessments, variables are also labeled as “Core” or “Deep Dive.” Core variables should be populated for all repositories based on public documentation (where available). Deep Dive variables may require direct engagements with repository stewards (e.g., requests for internal documentation, interviews) which might be necessary to understand certain repository features but may not be feasible for all assessments.  

</p>A subset of variables can be captured when an assessment is designed to address a specific need. For example, NICHD selected a specific set of variables to assess repositories with imaging data capabilities to ensure the Data Repository Finder provides accurate information relevant to sharing imaging data.  </p>

<br/><br/>

## Development Approach
Development of the Data Dictionary was informed by: 
- Metrics and themes derived from existing activities and documents, including:  

    - [The NICHD Strategic Plan](https://www.nichd.nih.gov/about/org/strategicplan)

    - [The NIH Strategic Plan for Data Science](https://datascience.nih.gov/nih-strategic-plan-data-science)

    - [The NICHD Data Strategy](https://www.nichd.nih.gov/sites/default/files/inline-files/202405_NICHD_Data_Sharing_Strategy_ODSS.pdf)

    - [The NIH Data Management and Sharing Policy](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/dms/policy-overview)

    - Supplemental Information to the NIH Policy for Data Management and Sharing: [Elements of an NIH Data Management and Sharing Plan](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-014.html)

    - [Metrics for Data Repositories and Knowledgebases: Working Group Report](https://datascience.nih.gov/sites/default/files/Metrics-Report-2021-Sep15-508.pdf)

    - [White House OSTP Desirable Characteristics of Data Repositories for Federally Funded Research](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf)

    - [RFI: Streamlining Access to Controlled Data from NIH Data Repositories](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-157.html)

    - [RFI: Updates and Long-Term Considerations for the NIH Genomic Data Sharing Policy](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-22-029.html)

    - [DOE Office of Science PuRe Data Resources](https://science.osti.gov/-/media/_/pdf/initiatives/pure/SC-PuRe-Data-Resource-Metric-Collection-Guidelines.pdf)

    - [SACHRP response to the DMS Policy](https://www.hhs.gov/ohrp/sachrp-committee/recommendations/august-12-2020-attachment-a-nih-data-sharing-policy/index.html)

- Feedback from the NICHD Data Ecosystem Working Group, chaired by the NICHD Office of Data Science and Sharing with participation from NICHD intramural and extramural staff.  

- Feedback from the NIH FAIR Working Group, led by the NIH Office of Data Science Strategy with participants from NIH Institutes, Centers, and Offices 

- Review of public repository documentation and policies 

- Alignment with FAIR data principles  

- Refinement through analyst review and subject matter expert validation 

Initial versions of the Data Dictionary were tested and iteratively refined resulting in the current version 1.2 with expanded and improved variable definitions. 

## Outcome
The resulting Data Dictionary provides a standardized, reusable framework that enables: 

- Consistent repository evaluation 
- Quantitative and qualitative ecosystem analysis 
- Identification of opportunities for improvements to or alignment across repositories

## <a id="how-to-use"></a>How to Use the NICHD Data Ecosystem Assessment Data Dictionary to Conduct Assessments
Follow these steps to apply the NICHD Data Ecosystem Assessment Data Dictionary to assess a repository: 

1. **Select a repository to assess**: Identify a repository relevant to NICHD or your research needs. 

2. **Download the Data Dictionary v1.2**: Use the version provided on [this GitHub page](https://github.com/NIH-NICHD-Ecosystem/E7-NICHD-Data-Ecosystem-Assessment/tree/main/Documentation) to ensure consistent variable definitions and response options. 

3. **Review repository materials**: Examine publicly available documentation, including: 
    - Repository website 
    - Submission guidelines 
    - Metadata schemas and data dictionaries 
    - Access and governance policies 

4. **Populate Ecosystem Assessment Variables (EAVs)**: For each variable in the Data Dictionary: 
    - Record the information if present. 
    - Document supporting evidence and reasoning 
    - Use existing standardized response categories where applicable 

5. **Review for consistency and completeness**: Confirm that variables used the correct response options and that the notes are sufficient to support later review or validation. 

6. When **multiple assessors** are engaged, they must then **reconcile** their findings to agree on the EAV Value. Generative AI may be used to help locate relevant information, but all machine-generated content should be validated by a human to populate a variable. Contact NICHDecosystem@nih.gov for more information regarding methods and effective prompts for AI-facilitated assessments.  

7. **Have a Subject Matter Expert review EAV values.** Engage knowledgeable NIH staff to do this final review. SMEs may provide additional useful information when they provide feedback in the “NICHD or SME Comments” column. Assessors should incorporate new information provided by SMEs into the “Additional Information” column after the feedback is resolved.   

## Notes on Use 

The Data Dictionary is designed for structured human review rather than automated extraction. Results reflect the availability of publicly documented information and may not capture all internal repository practices. Missing information should be recorded as “Not Found” rather than inferred. 

<br/><br/>


# User Stories
The following User Stories motivated and informed this Effort.


| S#  | User Story | Current Problem | User Goal |
|----|----|----|-----|
|1| [As a researcher, I want to find a repository that accepts both clinical and genomic data so that I can share all my study data in just one place ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-1.md) | Today, when I try to share data I do not know where to start. | My goal is to have somewhere to go that lets me look across repositories and find one that fits my dataset. |
| 64 | [As a researcher, I want to deposit medical imaging datasets such as MRI, DICOM, radiographs, and histological images in an NIH-supported repository for public sharing and DMS Policy compliance. ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-64.md) | Some NIH repositories do not accept medical imaging data, and domain-specific repositories (e.g., FaceBase) have narrow inclusion criteria that exclude many imaging types. | My goal is to find an NIH-supported repository that broadly accepts and shares diverse imaging datasets to facilitate research and meet data-sharing requirements. |
| 77 | [As an NICHD-funded researcher, I want access to a tool informed by repository assessments so that I can select a repository that aligns with NIH DMS Policy and supports my data type.  ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-77.md) | Today, researchers are often unaware repositories most suitable for their data type | My goal is to list details relevant to the DMS Policy in the Data Repository Finder to help researchers write their DMS Plans |
| 78 | [As NICHD ODSS leadership, I want to understand how existing NICHD repositories align with the NIH Data Management and Sharing (DMS) Policy so that we can advise on priorities for repository operations and enhancements. ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-78.md) | Today, researchers are often unaware repositories most suitable for their data type | My goal is to list details relevant to the DMS Policy in the Data Repository Finder to help researchers write their DMS Plans |
| 79 | [As NICHD ODSS leadership, I want an assessment of repositories’ metadata requirements so we can inform researchers on how to prepare their metadata.](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-79.md) | Today, researchers are often unaware of metadata best practices or requirements that improve data reuse. | My goal is to list metadata standards in the Data Repository Finder to help researchers prepare to share their data. |
| 80 | [As NICHD ODSS leadership, I want a consistent assessment framework applied across selective NICHD repositories so that we can draw data-driven conclusions about adherence to the NIH Data Management & Sharing Policy and FAIR principles ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-79.md) | Existing repository metrics do not sufficiently address DMS Policy expectations  | My goal is to have a comprehensive understanding of which data repositories can meet NIH data sharing needs. |

<br/>
