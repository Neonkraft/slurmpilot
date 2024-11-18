**TODOs**

* high: better support to launch series of experiments, see `notes/list_of_jobs.md`
* high: explain examples in readme
* high: pipeline to publish pypi version
* high: unify requirements and poetry
* high/medium: support using env variable for ssh passphrase
* medium: discuss getting out of your way philosophy of the tool
* medium: add way to show metadata, sp --metadata YOURJOB
* medium: report runtime in sp --list_jobs
* medium: make script execution independent of cwd and dump variable to enforce reproducibility
* medium: support local execution, see `notes/running_locally.md`
* medium: allow to copy only python files (or as skypilot keep only files .gitignore)
* medium: generates animation of demo in readme.md
* medium: allow to stop all jobs in CLI
* medium: rename SlurmWrapper to SlurmPilot
* medium: rerun/restart job (useful in case of transient error)
* medium: download in batch
* medium: chain of jobs
* low: support numerating suffix "-01", "-2" instead of random names
* low: doc for handling python dependencies

**DONE**

* high: show size of zipped archive
* high: support password and passphrase for ssh
* low: remove logging info ssh
* medium: suppress connection print output of fabrik (happens at connection, not when running commands)
* high: add description of CLI in readme.md
* high: add unit test actions
* high: support python wrapper
* medium/high: list jobs
* high: support subfolders for experiment files
* medium: add support to add cluster from CLI
* medium/high: script to install cluster (ask username, hostname etc)
* high: support defining cluster as env variable, would allow to run example and make it easier to explain examples in
  README.md
* medium: dont make ssh connection to every cluster in cli, requires small refactor to avoid needing SlurmWrapper to get
  last jobname
* high: handle python code dependencies
* high: add example in main repo
* medium: add option to stop in the CLI
* high: push in github
* high: allow to fetch info from local folders in list_jobs
* when creating job, show command that can be copy-pasted to display log, status, sync artifact
* support setting local configs path via local files
* test "jobs/" new folder structure
* tool to display logs/status from terminal
* make sp installed in pip (add it to setup)
* local configurations to allow clean repo, could be located in ~/slurmpilot/config
* set environment variables
* able to create jobs
* able to see logs of latest job
* run ssh command to remote host
* test generation of slurm script/package to be sent
* run sfree on remote cluster
* able to see logs of one job
* local path rather that current dir
* test path logic
* able to see status of jobs
* list all jobs and see their status
* enable multiple configurations
* "integration" tests that runs sinfo and lightweight operations
* option to wait until complete or failed
* stop job

