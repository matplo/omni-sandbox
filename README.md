# omni-sandbox
Sandbox for Omnilearn[ed] developments

# setup env etc

- note: this installs pyenv tool and heppyyier to install minimum HEP tools
  
```
curl -fsSL https://raw.githubusercontent.com/matplo/henv/main/henv | bash -s -- --install
```

```
henv . --run heyy install fastjet fjcontrib lhapdf hepmc3 pythia8 jewel heppyyier-utils
```

-- see https://github.com/matplo/heppyyier 

- you may need swig depending on your setup - try `henv . --run heyy install swig`

- test with
```
henv .
module load pythia8 fastjet 
heyy demos
python ./heppyyier_demos/demo_pythia_fastjet.py
```

- for latest support pytorch+mps on a mac
```
henv . --run python -m pip install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```

- omnilearned
```
henv . --run python -m pip install omnilearned
```
