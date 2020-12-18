# ml_train_state_machine
A general state machine for ML training pipeline.


## Project structure 
```buildoutcfg
.
|- artefacts (Local artefacts storage - replaced by cloud storage in production)
  |- models (Store trained model artefacts)
  |- logs (Store model training process logs)
|- data  (Store all data files, use external DB in prod)
|- src (Consists of required entities for ML Training State Machine)
  |- evaluation
  |- notebooks
  |- pipelines
  |- processing
  |- training
|- requirements.txt  (all pip dependencies specification)
|- setup.py  (Module setup)
```