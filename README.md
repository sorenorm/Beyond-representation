# Beyond Representation

This repositoy contains the code for investigating 1) who is represented in European parliaments, 2) who gets to present their ideas in European parliaments, and 3) whose ideas are allowed to diffuse between parliamentary members.

## Data
This project uses the [ParlaMint 4.0](https://www.clarin.si/repository/xmlui/handle/11356/1859) and [Comparative Candidate Survey](https://www.swissubase.ch/en/catalogue/studies/11249/19602/overview), along with two lists of politicians' missing genders and birthdays (these can be made available upon request).

## Content
This repository contains two codebooks: [BeyondRepresentation_DiffusionModel.ipynb](https://github.com/sorenorm/Beyond-representation/blob/main/BeyondRepresentation_DiffusionModel.ipynb) and [BeyondRepresentationRCodebook.Rmd](https://github.com/sorenorm/Beyond-representation/blob/main/BeyondRepresentationRCodebook.Rmd). 

The BeyondRepresentation_DiffusionModel.ipynb contains the python code for collecting the raw ParlaMint 4.0 data into country-wise .csv files, as well as for fitting diffusion models to these data sets.

The BeyondRepresentationRCodebook.Rmd contains the R-code for creating the visualisations pertaining to this project as well as the statistical models.

## Diffusion model
The content-based diffusion model presented by [Logins & Karras (2019)](https://pure.au.dk/ws/portalfiles/portal/174871912/cnip.pdf) is employed for investigating how ideas diffuse between politicians. The original version of the model can be found [here](https://github.com/iconvk/LearningIndependentCascadeOnVK/tree/master).

## Contributing

Søren Orm Hansen is the first maintainer of this repository but anyone are welcome to clone this repository and do a pull request for review. Ensure methodologically strong citations that support your claims.

## License

MIT License

Copyright (c) 2024 Søren Orm Hansen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
