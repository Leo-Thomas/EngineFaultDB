# EngineFaultDB: A Novel Dataset for Automotive Engine Fault Classification and Baseline Results

<!-- ABOUT THE PROJECT -->
## About the project

This paper introduces EngineFaultDB, a novel dataset capturing the intricacies of automotive engine diagnostics. Centered around the widely represented C14NE spark ignition engine, data was collected under controlled laboratory conditions, simulating various operational states, including normal and specific fault scenarios. Utilizing tools such as an NGA 6000 gas analyzer and a USB 6008 data acquisition card from National Instruments, we were able to monitor and capture a comprehensive range of engine parameters, from throttle position and fuel consumption to exhaust gas emissions. Our dataset, comprising 55,999 meticulously curated entries across 14 distinct variables, provides a holistic picture of engine behavior, making it an invaluable resource for automotive researchers and practitioners. For evaluation, several classifiers, including logistic regression, decision trees, random forests, support vector machines, k-nearest neighbors, and a feed-forward neural network, were trained on this dataset. Their performance, under standard configurations and a simple neural network architecture, offers foundational benchmarks for future explorations. Results underscore the dataset's potential in fostering advanced diagnostic algorithms. As a testament to our commitment to open research, EngineFaultDB is freely available for academic and industrial use. Future work involves expanding the dataset's diversity, exploring deeper neural architectures, and integrating real-world automotive conditions.

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/EngineFaultDB

## Data set description

This dataset consists of 59,000 entries spanning across 14 distinct variables, capturing both standard operational metrics and specific fault conditions. 

Regarding the variables of the dataset, these are:

* **Manifold Absolute Pressure (MAP):** A measure of the pressure within the intake manifold, crucial for the engine's electronic control system to regulate fuel injection and ignition timing.
* **Throttle Position Sensor (TPS):** Provides information about the position of the throttle, influencing fuel injection, ignition timing, and other engine parameters.
* **Force:** Represents the engine's torque or rotational force.
* **Power:** Quantifies the rate at which work is done or energy is transferred in the engine.
* **Revolutions Per Minute (RPM):** Indicates the engine's speed, detailing how many times the engine's crankshaft rotates per minute.
* **Fuel consumption L/H:** Illustrates the engine's fuel consumption rate.
* **Fuel consumption L/100KM:** Relays the engine's fuel efficiency over a given distance.
* **Speed:** The vehicle's travel speed.
* **Carbon monoxide (CO):** CO concentration in the exhaust gases.
* **Hydrocarbons (HC):** Concentration of unburnt hydrocarbons in the exhaust.
* **Carbon dioxide (CO2):** CO2 concentration in the exhaust, indicative of combustion efficiency.
* **Oxygen (O2):** Oxygen amount in the exhaust, offering insights into the combustion process.
* **Lambda:** The air-fuel equivalence ratio.
* **Air-Fuel Ratio (AFR):** Ratio of air to fuel in the combustion chambers.
  
The percentage distribution of data according to each fault type is as follows:

| Label    | Amount  | Percent (\%) |
|----------|---------|--------------|
| Fault type 0  | 18,000 | 30.5 |
| Fault type 1  | 11,999 | 20.3 |
| Fault type 2  | 15,000 | 25.4 |
| Fault type 3  | 14,001 | 23.7 |

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Mary Vergara - [LinkedIn](https://www.linkedin.com/in/mary-josefina-vergara-9ba47561/) - vmaryjose@gmail.com

Diego Rivera - [LinkedIn](https://www.linkedin.com/in/silvanakescobar/) - nrivera@ups.edu.ec

Francklin Rivas-Echeverría - [LinkedIn](https://www.linkedin.com/in/francklin-rivas-echeverria-514180144/) - frivas6@gmail.com

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - theleothomasramos@gmail.com

<br>
<br>


<p align="right">(<a href="#top">back to top</a>)</p>
