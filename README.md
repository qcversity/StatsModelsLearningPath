# Statistical Modeling Learning Path with Python


The **Statistical Modeling Learning Path with Python**, is a comprehensive resource
for learning statistical and econometric modeling with Python. 
This repository serves as an interactive book, offering a blend of theory and practical examples to help you master statistical and econometric modeling using Python.

This repository is also used as the main resource for my youtube channel and live lectures. 

### What You'll Find Here

1. **Comprehensive Tutorials:** Step-by-step guides and tutorials that cover a wide range of topics from basic statistical concepts to advanced statistical models. Each tutorial is supplemented with Python code examples, making it easier for learners to grasp the practical aspects of the theory.

2. **Real-World Applications:** We firmly believe in learning by doing. Therefore, this repository includes numerous real-world case studies and projects. These practical applications demonstrate how statistical models can be effectively utilized in various industries and research fields.

3. **Interactive Notebooks:** To enhance the learning experience, we provide interactive Jupyter notebooks. These notebooks allow you to run code, visualize data, and see the results of statistical modeling firsthand.

4. **Resource Library:** A curated collection of resources, such as research papers, books, and online articles, which will help you dive deeper into specific topics of interest.

5. **Community Contributions:** We encourage contributions from the community. Whether it's improving the existing content or adding new resources, your input is invaluable in making this a living, evolving educational tool.

## Target Audience

- **This learning path is designed for:**

1. **Beginners:** If you are new to statistical modeling or Python, you will find the initial modules particularly helpful. They are crafted to help you build a solid foundation.

2. **Intermediate Learners:** For those who already have some background in these fields, this repository offers advanced topics and complex project examples to challenge and enhance your skills.

3. **Experts:** Even if you are an expert, this repository serves as a great reference tool and a source for staying updated with the latest trends and methodologies in statistical modeling.

## Prerequisites

1. Basic knowledge of Python programming.
2. Fundamental understanding of mathematics, linear algebra, probability and statistics.

## Python Libraries used for This project

In this project we used several Python libraries:

- Numpy
- Scipy
- Sympy
- Pandas and Polars
- statsmodels
- Matplotlib
- Seaborn 

## Getting Started

To get started with StatsModels Learning Path:

### Clone the repository to your local machine.

```
git clone https://github.com/qcversity/StatsModelsLearningPath.git
```

or

```
gh repo clone qcversity/StatsModelsLearningPath
```

### Setup The Environment

In this section you will be guided on how to set up your environment using three tools, `mamba`, `conda` and `venv`. Feel free to use any other tool you use in your development.

#### Using `Mamba` Package Manager

1. Create a virtual environment using the `environment.yml` file

```
mamba env create -f environment.yml
```

Alternatively you can use the next command to create the environment:

```
mamba env create -f environment.txt -n smlpenv
```

2. Activate the newly created virtual environment

```
mamba activate smlpenv
```


#### Using `conda`

If `conda` is your main package manager you can set up your environment using the following command:

```
conda create -n smplenv --file package-list.txt
```

#### Using `venv` Virtual Environment Tool

If you are using native Python tool `venv` for virtual environment:

1. Create a folder for this project, please use a command Line Interpreter such as Terminal or Windows command prompt:

```
mkdir StatsModeling
```

Go this created directory

```
cd StatsModeling
```

2. Create a virtual environment first:

```
python -m venv venv
```

3. Activate the virtual environment

On Linux-Based systems:
```
source venv/bin/activate
```

On Windows system:

```
venv\Scripts\activate
```

4. Install the dependencies

```
python -m pip install -r requirements.txt
```

### How to Use This Learning Space

This learning space has just launched, and while writing the content, they will be lectures and interactive sessions in the form of Jupyter Notebooks:

1. First you need to read the lectures
2. Navigate to the Jupyter Notebooks for interactive sessions.
3. Solutions will be available in Notebooks Solutions

## Contributing

We welcome contributions to Statistical Modeling Learning Path! If you're interested in contributing, here's how you can do it:

1. **Fork the Repository**: Start by forking the repository to your GitHub account.
2. **Make Your Changes**: Add your content, fix bugs, or implement new features.
3. **Submit a Pull Request**: After making your changes, submit a pull request to the main repository.
4. **Code Review**: Your changes will be reviewed, and if everything is in order, they will be merged into the project.

When contributing, please follow these guidelines:

  - Ensure your code is well-documented.
  - Adhere to the existing coding style and standards.
  - Update the documentation if you're adding new features or making changes that affect how users interact with the project.


## License

The Statistical Modeling Learning Path is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


## Contact
For questions or feedback, please open an issue in the repository, or contact us directly via [email me](mailto:qcversity.info@gmail.com).


