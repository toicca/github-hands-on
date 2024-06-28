# Nico's amazing Pythia files

Here's my Pythia stuff from the Pythia exercises.

## Setup

**TODO**

## Running the code

In your Pythia Docker container you can run the Z boson analysis with

`pythia8-main93 -c z_boson.cmnd -o z_Default`

After running the analysis you will have a `.yoda` file, from which you can produce plots using

`rivet-mkhtml z_Default.yoda:Sim -o html_z`