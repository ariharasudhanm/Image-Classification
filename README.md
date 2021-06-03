# Image classification using CNN in Pytorch 

## About / Synopsis

* This is a model that is used for classificiation of Numbers from  0 to 9 created using convolutional neural networks in Pytorch.
* Project status: working/Model is getting optimized for the best performance


## Table of contents

Use for instance <https://github.com/ekalinin/github-markdown-toc>:

> * [Title / Repository Name](#title--repository-name)
>   * [About / Synopsis](#about--synopsis)
>   * [Table of contents](#table-of-contents)
>   * [Installation](#installation)
>   * [Usage](#usage)
>     * [Screenshots](#screenshots)
>     * [Features](#features)
>   * [Code](#code)
>     * [Content](#content)
>     * [Requirements](#requirements)
>     * [Limitations](#limitations)
>     * [Build](#build)
>     * [Deploy (how to install build product)](#deploy-how-to-install-build-product)
>   * [Resources (Documentation and other links)](#resources-documentation-and-other-links)
>   * [Contributing / Reporting issues](#contributing--reporting-issues)
>   * [License](#license)
>   * [About Nuxeo](#about-nuxeo)

## Implementation

Model is trained for the best accuracy and it can be used with the sample batch of data with images of size 1,28,28 converted to tensors.

## Usage
It is used to classify images from 0 to 9.
It can identify images of complex forms

### Features
* Usually image classification is traines using neural networks but in order to identify the images of complex forms and improper shapes, since CNN can surplus   amount of features and match it all over end to end of an image.

* It is trained using Adadelta optimizer to get the better accuracy since it restricts the large scale of past accumaulted gradients and doesn't requires a default learning rate.




### Content

Description, sub-modules organization...

### Requirements
It requires minimum of the following versions to run the file.
  jupyter version -->> 1.0.0
  torch version -->> 1.4.0
  torchvision -->> 0.5.0
  matplotlib version -->> 3.1.2

Optional requirements to view the images 
  numpy -->> 1.20.3 
  PIL 1.1. 7



### Limitations

Sample: <https://github.com/nuxeo-archives/nuxeo-features/tree/master/nuxeo-elasticsearch>

### Build

    mvn clean install

Build options:

* ...

### Deploy (how to install build product)

Direct to MP package if any. Otherwise provide steps to deploy on Nuxeo Platform:

 > Copy the built artifacts into `$NUXEO_HOME/templates/custom/bundles/` and activate the `custom` template.

## Resources (Documentation and other links)

## Contributing / Reporting issues

Link to JIRA component (or project if there is no component for that project). Samples:

* [Link to component](https://jira.nuxeo.com/issues/?jql=project%20%3D%20NXP%20AND%20component%20%3D%20Elasticsearch%20AND%20Status%20!%3D%20%22Resolved%22%20ORDER%20BY%20updated%20DESC%2C%20priority%20DESC%2C%20created%20ASC)
* [Link to project](https://jira.nuxeo.com/secure/CreateIssue!default.jspa?project=NXP)

## License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## About Nuxeo

Nuxeo Platform is an open source Content Services platform, written in Java. Data can be stored in both SQL & NoSQL databases.

The development of the Nuxeo Platform is mostly done by Nuxeo employees with an open development model.

The source code, documentation, roadmap, issue tracker, testing, benchmarks are all public.

Typically, Nuxeo users build different types of information management solutions for [document management](https://www.nuxeo.com/solutions/document-management/), [case management](https://www.nuxeo.com/solutions/case-management/), and [digital asset management](https://www.nuxeo.com/solutions/dam-digital-asset-management/), use cases. It uses schema-flexible metadata & content models that allows content to be repurposed to fulfill future use cases.

More information is available at [www.nuxeo.com](https://www.nuxeo.com).
