## Table of Contents
* [About the project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


## About the project
2 km river branch oudebeek_beek7 in the East of the Rummen catchment.
This is an automatically generated documentation based on the available scenario metadata. The current version of this 
document is from 2021-09-03.

### Built with
The scenario can be used in the following Landscape Models:
* xAquaticRisk version 2.34 and higher


## Getting Started
### Prerequisites
Make sure you use the latest version of the Landscape Model.

### Installation
Copy the complete scenario folder unaltered into the `scenario` sub-directory of your model. Reference the scenario
from the model parameterization. For details how to reference the scenario from the user parameterization, see the 
`README` of the model.


## Usage
The scenario adds the following macros to the Landscape Model:
* `:LandscapeScenario` (version 1.2)
* `:Temperature` (version 3)
* `:Hydrology` (version oudebeek_beek7-V-Ki-1.0-18112020)
* `:Catchment` (version oudebeek_beek7-V-Ki-1.0-18112020)
* `:TimeSeries` (version oudebeek_beek7-V-Ki-1.0-18112020)
* `:Map` (version 2.0.1)
* `:SiteInformation` (version 2.0.10)
* `:SpeciesParameters` (version 2.0.19)
* `:WaterTemperature` (version 2.0.10)
* `:Biomass` (version 2020.11.27)

### Roadmap
The scenario is final and not further developed. It will be, however, updated to reflect new requirements by the 
Landscape Model core and individual Landscape Model variants.


## Contributing
Contributions are welcome. Please contact the authors (see [Contact](#contact)) and see the `CONTRIBUTING` document.


## License
Distributed under the CC0 License. See `LICENSE` for more information.


## Contact
* Thorsten Schad - thorsten.schad@bayer.com
* Sascha Bub - sascha.bub@gmx.de


## Acknowledgements
* 
            Sebastian Multsch for hydrological, hydrographic and geospatial parts of the scenario
        
* Tido Strauß for the StreamCom parameterization
