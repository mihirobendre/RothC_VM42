This implementation of RothC simplifies its usage for carbon projects, especially ones under Verra's VM0042 methodology, by allowing for simultaneous runs in the project and baseline scenarios, while storing the results in a single output file.
This implementation reduces the repetition involved in separately running project and baseline scenarios for a project, which can save time, especially when tinkering with the model input and performing multiple runs.

The code builds upon [RothC's original implementation](https://www.rothamsted.ac.uk/rothamsted-carbon-model-rothc)

Instructions:
- Running the code: Open up the command line, and type `python RothC_Py.py`.
- Editing inputs: Open up csv files for inputs, and insert project-specific information.
- Seeing results: Open the year_results or month_results for annual or monthly results, respectively.
