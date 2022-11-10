# Project 1


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project implement different tasks to predict `gross income`, `Unit price`, `Day of week`, `gender`, `customer type` and analyze relationship between attributes. 

The dataset is one of a historical sales of supermarket company which has recorded in 3 different branches for 3 months data. This dataset includes 1000 data of each of these attributes:

```
**Invoice id**: Computer generated sales slip invoice identification number.

**Branch**: Branch of supercenter (3 branches are available identified by A, B and C).

**City**: Location of supercenters.

**Customer type**: Type of customers, recorded by Member for customers using member card and Normal for without member card.

**Gender**: Gender type of customer.

**Product line**: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel.

**Unit price**: Price of each product in US dollars.

**Quantity**: Number of products purchased by customer.

**Total**: Total price including tax.

**Date**: Date of purchase (record available from January 2019 to March 2019).

**Time**: Purchase time (10am to 9pm).

**Payment**: Payment used by customer for purchase (3 methods are available - Cash, Credit card and Ewallet).

**COGS**: Cost of goods sold.

**Gross margin percentage**: Gross margin percentage.

**Gross income**: supercenter gross income in US dollars.

**Rating**
```

The data was visualized, analyzed, cleaned, preprocessed and used to train several regression and classification model. The data was split into 80:20.

After implementing performance evaluation metrics, the model gives us 90.3% on the prediction of `gross income`, 80% on the prediction of `Unit price` and 13% on the prediction of `Day of week`. The parameter values give us the most informative attribute when we classify `Gender` and `Customer type`, which is the combination of `Fashion accessories + Cash` and the combination of `Tuesday + Afternoon`, respectively.


For more detail, please see my report paper. [https://github.com/Danielyaoan/Supermarket-Sales.git](https://github.com/Danielyaoan/Supermarket-Sales.git)


<!-- GETTING STARTED -->
## Getting Started


### Dependencies

* NumPy

```sh
pip install numpy
```
* Pandas

```sh
pip install pandas
```

* scikit_learn
```sh
pip install scikit-learn
```

* MatPlotLib
```sh
pip install matplotlib
```


* Scipy
```sh
pip install Scipy
```

* joblib
```sh
pip install joblib
```


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Danielyaoan/Supermarket-Sales.git
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f requirements.yml
  ```

<!-- USAGE EXAMPLES -->
## Usage

Run the Train notebook once so it can automatically generate the file for model and dataset for each task. The Test notebook calls all necessary trained pipelines to evaluate performance in the test set.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Yao An Lee - danielyaoanlee@gmail.com

Project Link: [https://github.com/Danielyaoan/Supermarket-Sales.git](https://github.com/Danielyaoan/Supermarket-Sales.git)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements



## Thank you
