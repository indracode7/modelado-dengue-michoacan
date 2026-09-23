# modelado-dengue-michoacan

This project aims to develop a mathematical model and simulation of dengue propagation in the state of Michoacán, using real epidemiological data.

The evolution of dengue cases will be analyzed across epidemiological weeks to identify the behavior of the disease over time. These data will serve as the basis for building and evaluating a simulation model.

The data will be obtained from the Mexican Ministry of Health, specifically from the General Directorate of Epidemiology (DGE).

**Official source:**
https://www.gob.mx/salud/documentos/panorama-epidemiologico-de-dengue-2026

## Data used

The dataset contains individual records for each epidemiological week.

The main variables used for the project are:

* `ID_REGISTRO`
* `FECHA_SIGN_SINTOMAS`
* `ENTIDAD_RES`
* `MUNICIPIO_RES`
* `ESTATUS_CASO`
* `RESULTADO_PCR`
* `DICTAMEN`

The records corresponding to Michoacán will be selected using `ENTIDAD_RES`. The number of cases will be obtained by counting the corresponding records for each epidemiological week.
