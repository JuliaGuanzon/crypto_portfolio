# Cryptocurrency Portfolio Performance

Measuring portfolio performance can be very simple and straight forward. Calculating returns and volatility can be a breeze when you compare a few stocks and protfolios, but comparing more than that may prove to be disastrous. With this new cryptocurrency portfolio prototype, we can easily see which cryptocurrencies are the best performers. Not only can compare performance, but we can do it using the fewest features possible to give the user a summarized set of information.


---

## Technologies

In order for this program to run, this application must be used in JupyterLab, as it uses the Pandas/Python language. To run the program, it is essential to have JupyterLab installed. To ensure the code works, please open the file in a dev environment using python. It is also necessary to install Pandas in order to read/run the code.

The operating systems and program versions are mentioned below and are highly recommended when running the program.

**Systems**

[conda 4.10.3](https://docs.anaconda.com/anaconda/install/index.html) - Package manager, Environment Manager

python 3.7 - included in Anaconda

[JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) - Web-based user interface

[Pandas](https://pandas.pydata.org/) - Open source data analysis and manipulation tool

**Other Installations**

[PyViz](https://pyviz.org/) - Tools for data visualizations

[scikit-learn](https://scikit-learn.org/stable/getting_started.html) - Open source machine learning library that supports supervised and unsupervised learning.

---

## Installation Guide

As mentioned above, to ensure that there are no errors when running this application, the user or programmer must use JupyterLab to access the application file. 

Additional installs are needed before running the program. Please install in terminal, in a dev environment:

```JupyterLab
conda active dev
python -m ipykernel install --user --name dev
conda install -c conda-forge nodejs
conda deactivate

```
Once installed you should be able to open JupyterLab by the following code:

```
conda activate dev
jupyter lab
```

To exit out of JupyterLab hit: Ctrl + C

It is important to also install Pandas as the majority of code use is using language from Pandas.

```Pandas
conda activate dev
conda install pandas -y
conda deactive
```

Below are the hvplot and scikit-learn installs:

```
conda install -c pyviz hvplot -y

conda install scikit-learn -y
```

---

## Usage and Examples

To use the cryptocurrency portfolio performance prototype, the repository will need to be cloned from GitHub and into a local repository.

In the crypto_portfolio folder, you will want to use the 'crypto_investments.ipynb' file. Enter into the dev environment by commanding: 

```
 conda activate dev
```
Next, use the code:

```
jupyter lab
```
to run the file.

![image](https://user-images.githubusercontent.com/84649228/132158743-d6666282-b000-4bb0-b26c-ba4fac99d3c5.png)


When using the file, each line of code must be individually ran to capture the data. This ensures any data that needs to be pulled gets included in future calculations as we start to build out formulas for analysis. It is important that we do not miss a line of code.

To quickly execute the code, use the keyboard shortcut: Shift + Enter.

The most important piece of code we need to run is the imports. Without these, nothing would work.

![image](https://user-images.githubusercontent.com/84649228/132158781-51440311-ead3-469a-8e72-def743f83e89.png)

First, the user is provided with the price change percentage for all cryptocurrencies, as well as a graphed version.

![image](https://user-images.githubusercontent.com/84649228/132158919-5e63b1e2-111d-459d-a69a-17b045e5f77d.png)

Next, the application scales the data and focuses on finding the best value for 'k' for the K-means algorithm, which aids in building our clusters around a centroid.

![image](https://user-images.githubusercontent.com/84649228/132159340-fb1045d9-38f0-47aa-a30e-a0b3afb11da4.png)

To efficiently summarize the information needed, the calculation of PCA is used. PCAs are tested and clusters are plotted as well.

![image](https://user-images.githubusercontent.com/84649228/132159473-7ace0740-c01b-40d6-bae2-ca73da05b003.png)


In the end, the user is presented with a comparison of the original data and PCA data of the elbow curve and the cluster results. The elbow curve comparison shows that both ways agree that four is the best value for 'k'. In the cluster results, the original data is clearly stated, while the PCA condenses the information.

![image](https://user-images.githubusercontent.com/84649228/132159996-fd7da6d5-2b98-4b01-8d48-bc610e7a50b4.png)
![image](https://user-images.githubusercontent.com/84649228/132160009-a53b2906-1ee8-41c8-acaf-f89ddc66e365.png)


---

## Contributors

[Julia Guanzon](www.linkedin.com/in/julia-guanzon)

## License

GPL-3.0 License
