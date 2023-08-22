# Google Colab
JS Experiments with Google Colab (jupyter notebook environment)

## Colab Access to Local Drive
 - Initial Package Installation (within a conda environment)
   - Install Google-Colab: conda install -c conda-forge google-colab
   - Install Jupyter server extension: conda install -c conda-forge jupyter_http_over_ws
   - (Optional) Install ipykernel (interactive Python shell and jupyter kernel): conda install -c anaconda ipykernel
- Initialize local jupyter server instance
   - Type at CIL: jupyter notebook --port=9090 --NotebookApp.allow_origin='https://colab.research.google.com'
   - Copy the backend URL from CIL output (ex: http://localhost:9090/?token=fc426bf37e71d41559f68c88ff9f5e98399e13a97f8d6729)
- Open Google Colab and Connect to a Local Runtime
  - Open webrowser and head to: https://colab.research.google.com/
  - Start an iPython notebook
  - Navigate to "Connect" in the Colab notebook and select "Connect to a local runtime"
  - In "Local Connection Settings" window, enter the copied URL backend information  


