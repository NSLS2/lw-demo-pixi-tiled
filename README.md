# Use pixi to run a web service

Download and run Tiled server using a pixi manifest.

## Instructions

1. Start a Horizon VDI session using the "N2SN Linux Desktop".

    <https://vdi.nsls2.bnl.gov>
   
2. Clone this repository into your $HOME directory.

    ```shell
    git clone https://github.com/NSLS2/lw-demo-pixi-tiled
    ```

3. Run the "default" pixi task, called `start`.

    ```shell
    pixi run start
    ```

4. Open a web browser and paste the URL from the terminal output. Include the API key.

    Example: <http://127.0.0.1:8000?api_key=461e08317...>

---
This was created as a Learning Week demonstration, March 2026.
