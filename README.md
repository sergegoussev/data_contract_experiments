# Data contract experiment

Experiments to set up data contracts using [data contract cli](https://cli.datacontract.com/) and set up a [data catalog](https://datacontract.com/examples/index.html). The experiment is to try out the technology and to try to apply it to creating a data catalog of datasets that can be used for in the price statistics discipline. 

## Steps:

### Add new dataset
1. Create a new `datacontract.yaml` into the `\datasets` folder
2. **TEMP** navigate into the `\datasets` folder and then using the conda environment specified in `environment.yml`, run `datacontract catalog --output ../catalog/`. this outputs the catalog index.html and the other data contracts into a new `\catalog` folder.

## Folder structure

```
├── datasets               # Placeholder of the data contracts for each dataset
└── catalog                # folder where the data catalog works
```
