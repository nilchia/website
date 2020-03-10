---
site: freiburg
tags: devops
title: Storage issues and potential data loss
---

On Friday, we unfortunately experienced some data loss. Currently, we believe that some datasets created in the last two months were affected.

If your data was affected by this, the datasets will still appear in your history, but the data itself will be missing - i.e. if you click on the 'View' or 'Download' buttons, you will probably encounter an error or a white page.

If you try and run a job using one of the affected datasets as input, the job will fail with an error like 'Job 7225486's output dataset(s) could not be read'.

We are working on dealing with the situation and will update this blog-post with more information later today. If you have any questions, feel free to email us at galaxy@informatik.uni-freiburg.de.

We are truly sorry!

### Tips for re-creating your histories or re-running your results

* ensure that your input datasets are still available, re-upload them if needed
* use the reload button to re-run single tools
* [extract workflows from your history](https://training.galaxyproject.org/training-material/topics/galaxy-ui/tutorials/history-to-workflow/tutorial.html) and re-run them again