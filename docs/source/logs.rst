Latest Logs From Latest Build
==============================

Generated On: 2025-05-02 19:41:25 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/rmousavi-raspberry/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-05-02_19:20:13] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-05-02_19:20:31] STEP 2: Create topics started

  [INFO 2025-05-02_19:25:18] STEP 2: Completed

  [INFO 2025-05-02_19:25:40] STEP 3: producing data started

  [INFO 2025-05-02_19:25:55] STEP 4: Preprocessing started

  [INFO 2025-05-02_19:26:09] STEP 3: reading local file..successfully

  [INFO 2025-05-02_19:26:20] STEP 4a: Preprocessing started

  [INFO 2025-05-02_19:26:26] STEP 4: Preprocessing started

  [INFO 2025-05-02_19:26:36] STEP 4a: Preprocessing started

  [INFO 2025-05-02_19:26:53] STEP 7: Visualization started

  [INFO 2025-05-02_19:26:58] STEP 4c: Preprocessing 3 started

  [WARN 2025-05-02_19:27:22] STEP 7: Cannot make a connection to Viperviz on port 9005.  Going to try again...

  [WARN 2025-05-02_19:27:27] STEP 7: Cannot make a connection to Viperviz on port 9005.  Going to try again...

  [INFO 2025-05-02_19:27:33] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2025-05-02_19:28:45] STEP 9: Qdrant container.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant, v=0

  [INFO 2025-05-02_19:28:45] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2025-05-02_19:28:50] STEP 9: Starting privateGPT

  [WARN 2025-05-02_19:28:52] STEP 9: PrivateGPT container not found. It may need to be pulled if it does not start: docker pull maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2

  [INFO 2025-05-02_19:28:55] STEP 8: Starting docker push for: rmousavi/cybersecurityrtms-elastalink-3f10-ai-da47-amd64

  [WARN 2025-05-02_19:39:51] STEP 8: There seems to be an issue optimizing the container.  Here is the commit command: docker commit 9adecbfabe4e rmousavi/cybersecurityrtms-elastalink-3f10-ai-da47-amd64 - message=0.  Container may NOT pushed.

  [INFO 2025-05-02_19:41:18] STEP 10: Started to build the documentation

  [INFO 2025-05-02_19:41:51] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


