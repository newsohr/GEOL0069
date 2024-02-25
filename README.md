# GEOL0069

<!-- ABOUT THE PROJECT -->
## Assignment week 4

The task is to classify the echoes in leads and sea ice and produce an average echo shape as well as standard deviation for these two classes.

In addition, the echo classification is quantified against the ESA official classification using a confusion matrix.


<!-- GETTING STARTED -->
## Getting Started

The project is built on the notebook called Chapter1_Unsupervised_Learning_Methods.ipynb available on https://github.com/newsohr/GEOL0069/blob/main/Chapter1_Unsupervised_Learning_Methods.ipynb
<!-- ### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```
-->
  
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install essential packages.

For example,

```bash
pip install rasterio
```


## Usage

<!-- ```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

 USAGE EXAMPLES -->

The notebook starts with an introduction of unsupervised machine learning methods including K-means and Gaussian Mixture Model (GMM). The code of two algorithms is then implemented to classify sea ice and lead based on Sentinel-2 optical data, which produces images similar to the following:

![image](https://github.com/newsohr/GEOL0069/assets/152040156/549021e9-c887-4689-bf53-1b5ac3f8bb32)


The second part is the classification of Sea ice and lead based on Sentinel-3 altimetry data. The plots involve the classification of echoes of sea ice and lead from ESA official data and the prediction of GMM. After that, the average of sea ice and leads classification is plotted with the standard deviation filled in.

In the end, a confusion matrix is computed to quantify the classifications of prediction against true values.


<!-- ROADMAP 
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues). 
-->



## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. 


## Contact

Rhoswen - rhoswen.zeng.20@ucl.ac.uk

Project Link: https://github.com/newsohr/GEOL0069

## Acknowledgments

* []() The input ESA official data is fetched using Google Earth Engine.


## Reference

* []() Quartly GD, Rinne E, Passaro M, Andersen OB, Dinardo S, Fleury S, Guillot A, Hendricks S, Kurekin AA, Müller FL, et al. Retrieving Sea Level and Freeboard in the Arctic: A Review of Current Radar Altimetry Methodologies and Future Perspectives. Remote Sensing. 2019; 11(7):881. https://doi.org/10.3390/rs11070881



