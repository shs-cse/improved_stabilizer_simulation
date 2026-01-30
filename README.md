This repo contains a self-contained slides on stabilizer simulation, mostly focusing on Aaronson and Gottesman's paper on improved stabilizer simulation.

# Improved Simulation of Stabilizer Circuits
- Scott Aaronson
- Daniel Gottesman
- https://arxiv.org/abs/quant-ph/0406196
- Slide author's [annotated notes](public/Aaronson-Gottesman_stabilizer_simulation_0406196.pdf) over the paper

# Marimo Notebook
- The slides were created using marimo notebook.
- Once `marimo` installed (maybe use with `uv`), use the following command to run on your computer.
    ```sh
    marimo edit main.py --sandbox
    ```
- For exporting the notebook (slides) as webpages, the following command was used.
    ```sh
    marimo export html-wasm --mode run --no-show-code -o docs -f main.py --sandbox 
    ```
- Then the `/docs` folder was hosted on github pages.