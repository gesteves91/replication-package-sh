# Replication Package for the Software Health Project

This project is capable of prediction the proportion of defective commits, thus we analyze the project health . The dataset is composed of GitHub data gathered from GHTorrent REST API.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have installed some packages to use our replication project. The *requirements.txt* file in the root directory stores all the necessary packages. We strongly recommend using either Linux or Mac to execute this package. Windows is not supported by default, but you may get it working there too.

<h4>1) Requirements Installation</h4>

Practical example assuming you are in the root project:

```shell
virtualenv -p python3 venv
source venv/bin/activate
python3 install -r requirements.txt
```

<h4>2) Compressed Data</h4>

We should execute the following command to get the data in the root directory:

```bash
unzip github-data.zip
```

**Note that you need *zip* installed on your machine.**

<h4> Authors </h4>

Geanderson E. dos Santos - PhD Candidate

<h4> License </h4>

This project is licensed under the MIT License - see the [LICENSE.md](License.md) file for details.

<h4> Acknowledgments </h4>

We would like to thank [GHTorrent](https://ghtorrent.org/) as it was the main provider of the data.









