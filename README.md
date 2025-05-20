# Price change in perishable goods
Price change in perishable goods (raspberries).

## Framework installation

Log into a linux machine with Anaconda installed.

In the terminal do:

1. Clone the repository:
  ```
  git clone git@github.com:CristobalMe/price-changes-in-perishable-goods.git
  ```
2. Access the code:
  ```
  cd price-changes-in-perishable-goods
  ```

3. Install the conda enviroment:
  ```
  conda env create -f environment.yaml
  conda activate tda
  conda develop .
  ```
  
3.1 Update the conda enviroment:
   ```
   conda env update --file environment.yaml --prune
   ```
