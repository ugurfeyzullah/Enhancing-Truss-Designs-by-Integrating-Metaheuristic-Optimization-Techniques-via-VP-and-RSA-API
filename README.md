# Intelligent Optimization of Steel Structures by employing RSA-API through Revit-Dynamo
![120-bar Dome API with buckling_2024-03-29_02-49-49](https://github.com/ugurfeyzullah/Enhancing-Truss-Designs-by-Integrating-Metaheuristic-Optimization-Techniques-via-VP-and-RSA-API/assets/149387821/f52bd773-4d09-4b9c-8f2e-f2595d42febb)


**Quick Links:** [Documentation](#features) / [Installation](#installation) / [Usage](#usage) / [Paper](#acknowledgments) /  [Citation](#citation) / [Contact](#contact)

This repository hosts the implementation of an innovative methodology for the intelligent optimization of steel structures using a BIM-based visual programming platform and tools. The methodology leverages Metaheuristic Algorithms (GA), Visual Programming (VP) with Dynamo, and FEA with RSA-API to minimize structural weight while satisfying stress and displacement constraints. The primary goal is to create sustainable, affordable, and eco-friendly designs by leveraging the power of artificial intelligence and digital technologies. The research focuses on optimizing the design of spatial trusses using two metaheuristic algorithms: Genetic Algorithm (GA) and Particle Swarm Optimization (PSO) by employin Python libraries and different type of constraint handling techniques (CHTs), in conjunction with parametric modeling tools and numerical structural analysis.

This project was conceptualized and performed during the research stay at the research group of Jun.-Prof. Dr. Reza Maalek, the GOLDBECK endowed chair in Digital Engineering and Construction (DEC) at the Institute of Technology and Management in Construction (TMB) of the Karlsruhe Institute of Technology (KIT). The findings and experimental details were presented in the IASS conferance. The author contributions (based on MDPI’s categorization) are as follows:

Conceptualization, R.M. and F.Y.; methodology, R.M., and F.Y.; software, F.Y.; validation, F.Y.; formal analysis, F.Y.; investigation, R.M. and F.Y.; resources, R.M.; data curation, F.Y.; writing—original draft preparation, F.Y.; writing—review and editing, R.M.; visualization, F.Y.; supervision, R.M.; project administration, R.M.; funding acquisition, R.M.


https://github.com/ugurfeyzullah/Enhancing-Truss-Designs-by-Integrating-Metaheuristic-Optimization-Techniques-via-VP-and-RSA-API/assets/149387821/a43f1b3c-0d15-4f2a-9142-f82d8777e4aa


## Motivation

The construction industry faces the challenge of meeting the demands of contemporary societies for efficient and optimized structures. Traditional design workflows often lead to compromises and inefficiencies. This project addresses these challenges by proposing a seamless integration of structural optimization (SO) into the BIM environment, facilitating better collaboration between architects and engineers and promoting the use of sustainable materials and design practices.

## Features

- **Integration with BIM Tools**: Utilizes Dynamo for visual programming and RSA for FEA to streamline the structural design and optimization process.
- **AI-Based Metaheuristic Optimization**: Employs metaheuristic algorithms for efficient search and optimization of structural parameters.
- **Finite Element Analysis**: Uses Robot Structural Analysis (RSA) API for accurate stress, weight, and displacement calculations.
- **Visual Programming**: Leverages the power of Dynamo to facilitate the parametric modeling and optimization process.
- **Constraint Handling**: Incorporates different types of CHTs to show efficiency of provided codes.



https://github.com/ugurfeyzullah/Enhancing-Truss-Designs-by-Integrating-Metaheuristic-Optimization-Techniques-via-VP-and-RSA-API/assets/149387821/c2c92639-3493-4cd0-8255-5bf00be0ec17




## Getting Started

### Prerequisites

- Dynamo 
- Robot Structural Analysis Professional
- PyMoo library for Python
- Numpy library for Python
- Basic knowledge of structural engineering and optimization

### Installation

1. Clone this repository to your local machine.
2. Ensure you have the required software installed (Dynamo, RSA).
3. Customize your Dynamo's Python by following steps explained on https://github.com/DynamoDS/Dynamo/wiki/Customizing-Dynamo's-Python-3-installation
4. Ensure you have the required Python libraries on your Python for Dynamo.
5. Use the provided Dynamo scripts and provided RSA template.

## Usage

1. **Model Preparation**: Start by preparing your parametric structural model in Dynamo.
2. **RSA Preparation**: Ensure your RSA template has all sections mentioned on Dynamo imputs.
3. **Optimization with Dynamo**: Open the provided Dynamo script to perform optimization. Adjust input parameters as needed for your specific structural design requirements and change the provided Python code if needed.
4. **Analysis in RSA**: Provided script will use RSA-API for detailed FEA as part of the optimization loop.
5. **Evaluation**: You can use different constraint handling techniques or different algorithms for evaluation.
   
## Contributing

Contributions are welcome! If you have improvements or bug fixes, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -am 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Citation

If you have used our framework for research purposes, you can cite our publication by:

(To be added)

BibTex:
(To be added)

## Contact

- Feyzullah YAVAN - [www.linkedin.com/in/ugurfey](www.linkedin.com/in/ugurfey) - feyzullah.yavan@kit.edu

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.
