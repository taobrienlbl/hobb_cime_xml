# Getting started

Clone this repository and place it in your home directory as `~/.cime`, e.g.:

`git clone https://github.com/taobrienlbl/hobb_cime_xml.git ~/.cime`

CESM simulations can then be run by specifying `--machine hobb`, e.g.:

```bash
/usr/local/share/CESM2.2.0/cime/scripts/create_newcase \
    --compset FDABIP04 \
    --res T42z30_T42_mg17 \
    --case dabi \
    --machine hobb
```

By default, the `bld`, `run`, and `archive` directories for CESM will be placed in `/scratch/${USER}/tmp/cesm`

