# Dataset Preparation

## Reformatting the Original Dataset

### Waymo Dataset
To reformat Waymo's scenario protocol buffer data, download the dataset and then specify the `--wod_path` argument to the local path of the Waymo Motion dataset. Finally, execute the following command to split the data:

```bash
python scripts/preprocess/process_wod_data.py --wod_path your/path/to/waymo/motion/dataset
```

### Nuplan Dataset
For instructions on setting up the Nuplan dataset, refer to [Nuplan Devkit Documentation](https://nuplan-devkit.readthedocs.io/en/latest/dataset_setup.html).

## Caching the Dataset
To train efficiently, it is essential to cache the data first. Follow these steps:

### Waymo Dataset
Run the following script to cache the Waymo dataset:

```bash
sh ./scripts/preprocess/cache_wod_data.sh
```

### Nuplan Dataset
Run the following script to cache the Nuplan dataset:

```bash
sh ./scripts/preprocess/cache_nuplan_data.sh
```

## Nexus-data
To enhance the model's ability to handle safety-critical scenarios such as cut-ins, rear-end collisions, and others, we constructed a dedicated safety-critical dataset named Nexus-data. This dataset follows the same format as the Nexus cached dataset. We have made it publicly available, and you can access it on [Hugging Face](https://huggingface.co/datasets/OpenDriveLab-org/Nexus_data/tree/main). More details about the dataset can be found in the Nexus paper.
