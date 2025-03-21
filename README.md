# Diet Formulation Calculator

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15029930.svg)](https://doi.org/10.5281/zenodo.15029930)

An interactive web-based calculator for formulating and optimizing experimental feed compositions. This tool helps researchers and nutritionists create iso-protein and iso-energetic experimental diets.

## Features

- Dynamic feed treatment setup
- Real-time nutrient calculations
- Automatic iso-protein and iso-energetic validation
- Smart optimization suggestions
- Easy ingredient copying between feeds
- Comprehensive nutrient analysis

## Usage

1. Enter the number of experimental feeds you want to create
2. Add ingredients to Feed 1 with their respective:
   - Ratio (%)
   - Protein content (%)
   - Lipid content (%)
   - Ash content (%)
   - Carbohydrate content (%)
3. Use the "Copy from Feed 1" button to duplicate ingredients to other feeds
4. Adjust ingredient ratios based on the optimization suggestions
5. Monitor the Results section for:
   - Total nutrient content
   - Energy content
   - Iso-protein and iso-energy validation

## Validation Criteria

- Protein difference: Maximum 2% variation allowed
- Energy difference: Maximum 50 kJ/g variation allowed
- Total ingredient ratio must equal 100%

## Energy Conversion Factors

- Protein: 23.6 kJ/g
- Lipid: 39.5 kJ/g
- Carbohydrate: 17.2 kJ/g

## Reference

National Research Council. (2011). *Nutrient Requirements of Fish and Shrimp*. National Academic Press, Washington, DC. DOI: [10.17226/13039](https://doi.org/10.17226/13039)

## Author

Dr Thiru Chenduran Somasundaram

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Citation

If you use this calculator in your research, please cite it as:

```bibtex
@software{somasundaram_2025,
  author       = {Somasundaram, Thiru Chenduran},
  title        = {Diet Formulation Calculator: A Tool for Iso-Protein and Iso-Energy Feed Formulation},
  month        = mar,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.15029930},
  url          = {https://doi.org/10.5281/zenodo.15029930}
}
``` 