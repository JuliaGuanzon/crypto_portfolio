# Cryptocurrency Portfolio Performance

Measuring portfolio performance can be very simple and straight forward. Calculating returns and volatility can be a breeze when you compare a few stocks and protfolios, but comparing more than that may prove to be disasterous. With this new cryptocurrency portfolio prototype, we can easily see which cryptocurrencies are the best performers. Not only can compare performance, but we can do it using the fewest features possible to give the user a condensed set of information.


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



When using the file, each line of code must be individually ran to capture the data. This ensures any data that needs to be pulled gets included in future calculations as we start to build out formulas for analysis. It is important that we do not miss a line of code.

To quickly execute the code, use the keyboard shortcut: Shift + Enter.

The most important piece of code we need to run is the imports. Without these, nothing would work.

![01_import](https://user-images.githubusercontent.com/84649228/126043950-a43d3c63-8054-46be-9a7c-6825b90cd56f.PNG)



---

## Contributors

[Julia Guanzon](www.linkedin.com/in/julia-guanzon)

## License

GPL-3.0 License
