# gguf_works

What this repo contains
- `llama_cpp_python_inference.ipynb` — a Colab-ready notebook that shows how to run inference
	with `llama-cpp-python` against a local GGUF model (example uses a model stored on Google Drive).

Quick start (Colab)
1. Open the notebook in Colab using the badge at the top of the notebook.
2. Mount Google Drive when prompted and place your `.gguf` model where the notebook expects it.
3. Run the cells in order: install `llama-cpp-python`, set `model_path`, then run the inference or interactive chat cells.

Quick start (local machine)
1. Install Python 3.8+ and pip.
2. Install the dependency:

```bash
pip install llama-cpp-python
```

3. Update `model_path` in the notebook (or in a short script) to point to your local `.gguf` file.
4. Run the example cell that creates `Llama(model_path=...)` and call the model.
License
- See the notebook and the model provider license for usage restrictions.
 
See the `LICENSE` file for repository-level licensing information.