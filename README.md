# Spike sorting school - Cajal - Bordeaux 2024

Material for the spike sorting/SpikeInterface training day, part of the [Cajal movement and motor control 2024](https://cajal-training.org/on-site/movement-and-motor-control-in-health-and-disease/).


**To do before the training:**

1. Install SpikeInterface, using the [installation guide](#installation) below
2. Download the [dataset for the tutorials](#dataset)



## Schedule


Tuesday 19th November

11:00-11:45 Introduction to spike sorting

11:45-12:300 Overview of SpikeInterface + demo


14:00 18:00 : SpikeInterface detailed handons and tutorials

  * Object interaction cookbook 15min
  * Probe handling 15min
  * Preprocessing  20min
  * Drift with generated data 20min
  * Postprocessing 20min
  * Visualization (Sortingview, Sigui) 20min
  * Metrics & Curation (Automerge, etc.) 20min
  * Sorting on your own dataset 30min

18:00 19:00 EMUsort Samuel Sober



Given the limited time, the hands-on session is more a follow-along guided tutorials.
You can download all notebooks on this [repo](https://github.com/samuelgarcia/-school_spike_sorting_cajal_bordeaux_2024).




## Installation

This procedure use the new [uv fast installer for python](https://github.com/astral-sh/uv).

**Procedure for Windows/Apple/Linux:**



1. On macOS and Linux. Open a terminal and do $ curl -LsSf https://astral.sh/uv/install.sh | sh
1. On windows. Open a powershell and do powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
2. exit session and log again.
3. Go to this page https://github.com/samuelgarcia/school_spike_sorting_neuralnet_saclay_2024
4. Click on **"code"** (green button) and download the zip. Etxract the zip.
5. open terminal or powershell
6. Go to the correct folder `cd C:/users/myusername/where_the_zip_is`
7. Create an empty env `uv venv si_env --python 3.11`
8. Activate the env `source si_env/bin/activate` (you should have (si_env) in your terminal)
9. `uv pip install -r requirements_tutorial.txt`

**Do not wait to do this during the tutorial, it can be time consuming**

For installtion, you can have more information [here](https://github.com/SpikeInterface/spikeinterface/tree/main/installation_tips)


## Dataset

Please download datasets from this link and unzip them:

https://drive.google.com/drive/folders/17RlgsMLheW82IMLMgmTFifVACebDZ8X5?usp=sharing
