# Google-Cloud-Platform-Examples

read through Apache Beam Python SDK Quickstart for environment set up: https://beam.apache.org/get-started/quickstart-py/#execute-a-pipeline-locally

In addition to the setup steps contained in the quickstart link above, install the Google Cloud SDK, https://cloud.google.com/sdk/downloads. Note that when installing the Cloud SDK the below command didn't work for me:
`./google-cloud-sdk/install.sh`

...I received this error:

`/System/Library/Frameworks/Python.framework/Versions/2.7/Resources/Python.app/Contents/MacOS/Python: can't open file '/Users/ryanchase/Documents/bin/bootstrapping/install.py': [Errno 2] No such file or directory`

Therefore, I'd recommend using the interactive installer instead:
https://cloud.google.com/sdk/downloads#interactive
