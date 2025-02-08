# dataform_genz_fashions

* [Dataform installation](https://cloud.google.com/dataform/docs/use-dataform-cli)
 * Install Node JS
  
  ## Initilise dataform
  ```
  dataform init . PROJECT_NAME DEFAULT_LOCATION
  ```
  
  ## Get bigquery credentials
  ```
  dataform init-creds
  ```

  ## Create node modules
  ```
  dataform install
  ```

  ## Compile project
  ```
  dataform compile
  ```

  ## Compile with runtime variables
  ```
  dataform compile --vars=SAMPLE_VAR=SAMPLE_VALUE,foo=bar
  ```

  ## Run whole project
  ```
  dataform run --vars=SAMPLE_VAR=SAMPLE_VALUE,sampleVar2=sampleValue2
  ```

  ## Run full refresh
  ```
  dataform run --full-refresh
  ```