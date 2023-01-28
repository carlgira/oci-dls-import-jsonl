# OCI Datalabeling import jsonl

Script to import jsonl into datalabeling service. Tested for a dataset on OBJECT_DETECTION on images.

# Configure
```bash
python3 -m venv .venv
pip install -r requirements.txt
```

# Run

1. From an existing datalabeling project, export dataset and the records files. Save the jsonl on this folder.

2. Follow the instructions to configure oci cli and to create API keys to authenticate against OCI that are in this blog https://medium.com/@carlgira/install-oci-cli-and-configure-a-default-profile-802cc61abd4f

3. Open jupyter
```bash
jupyter-lab
```
4. Configure the second cell with your own env env.

5. Run all cells

