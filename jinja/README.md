## Requisitos

Instala Anaconda:

- Anaconda Distribution: https://www.anaconda.com/products/distribution

## Entorno

1. Crea un entorno virtual con Anaconda:

    ```bash
    conda create --name jinja-sandbox python=3.10 jupyter
    ```

2. Activa el entorno:

    ```bash
    conda activate jinja-sandbox
    ```

3. Instala los paquetes necesarios:

    ```bash
    pip install -r requirements.txt
    ```

## Uso

```bash
jupyter notebook jinja-sandbox.ipynb
```