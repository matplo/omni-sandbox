# omni-sandbox
Sandbox for Omnilearn[ed] developments

# setup env etc

- note: this installs pyenv tool and heppyyier to install minimum HEP tools
  
```
curl -fsSL https://raw.githubusercontent.com/matplo/henv/main/henv | bash -s -- --install
henv . --run heyy install fastjet fjcontrib lhapdf hepmc3 pythia8 jewel heppyyier-utils
```

- you may need swig depending on your setup - try `heyy install swig`