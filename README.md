UDF Distribution Test: Git Repo Code to Workers
Test Plan:
Test 1: Show that imports from Git Repo FAIL on workers (without addPyFile)
Test 2: Fix with addPyFile and show it works
Test 3: Monitor which nodes execute the UDFs
Prerequisites:

Cluster with at least 1 driver + 1 worker
Git Repo with taxi_udfs/calculations.py module
Update REPO_PATH below to match your workspace path!
