# 🎹 Polars vs. Pandas Benchmarking 🥁

A Jupyter Notebook benchmarking Polars vs. Pandas on Austin's Real-Time Road Conditions dataset.

## Setup Instructions (for MacOS)

### Step 1: Install Dependencies

1. Clone this repository:

   ````bash
   git clone https://github.com/ThatOrJohn/polars-pandas-benchmark.git
   cd polars-pandas-benchmark```

   ````

2. Create a virtual environment

   ````python3 -m venv .venv
   source .venv/bin/activate```

   ````

3. Install required packages
   `pip install -r requirements.txt`

### Step 2: Download the Dataset

The dataset (Real-Time_Road_Conditions.csv, 852MB uncompressed) is sourced from the Austin Open Data Portal.

Download the dataset: [Real-Time Road Conditions Dataset](https://data.austintexas.gov/Transportation-and-Mobility/Real-Time-Road-Conditions/ypbq-i42h/about_data)

Save it as Real-Time_Road_Conditions.csv in the same directory as the notebook.

### Step 3: Run the Notebook

Start Jupyter Notebook:

`jupyter notebook`

Open benchmark_polars_pandas.ipynb and run the cells.
