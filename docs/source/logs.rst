Latest Logs From Latest Build
==============================

Generated On: 2026-03-15 17:48:24 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Vangala09/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2026-03-15_17:43:42] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2026-03-15_17:43:46] STEP 2: Create topics started

  [INFO 2026-03-15_17:43:59] STEP 2: Completed

  [INFO 2026-03-15_17:44:07] STEP 3: producing data started

  [INFO 2026-03-15_17:44:10] STEP 4: Preprocessing started

  [INFO 2026-03-15_17:44:12] STEP 4: Preprocessing started

  [INFO 2026-03-15_17:44:12] STEP 3: reading local file..successfully

  [INFO 2026-03-15_17:44:15] STEP 5: Machine learning started

  [INFO 2026-03-15_17:44:20] STEP 6: Predictions started

  [INFO 2026-03-15_17:44:22] STEP 7: Visualization started

  [INFO 2026-03-15_17:44:28] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2026-03-15_17:44:34] STEP 9b: Starting ollama server

  [INFO 2026-03-15_17:44:52] STEP 8: Starting docker push for: reshmareddy09/tml-multi-agenticai-iot-3f10-ml_agenticai-4f96-amd64

  [INFO 2026-03-15_17:45:14] STEP 9b: Ollama container.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-cpu-amd64-llama3-tools, v=125

  [INFO 2026-03-15_17:45:14] STEP 9b: Success starting Agentic AI.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-cpu-amd64-llama3-tools

  [INFO 2026-03-15_17:48:08] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit 3e757151f356 reshmareddy09/tml-multi-agenticai-iot-3f10-ml_agenticai-4f96-amd64 - message=0

  [INFO 2026-03-15_17:48:24] STEP 10: Started to build the documentation

  [INFO 2026-03-15_17:48:24] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


