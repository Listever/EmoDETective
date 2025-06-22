# Scripts
## Training
## Script Naming Convention

All experiment scripts in this project **must** follow the unified versioning and naming convention below:

`v{Stage}{Train}{Ablation}{Dataset}_description.sh`


Each digit/letter stands for a specific dimension of your experiment:

| Position | Field           | Example Values         | Description                                                        |
|----------|----------------|-----------------------|-----------------------------------------------------------------------------------|
| 1        | Stage          | 0, 1, 2, 3            | 0 = Raw model / baseline; 1 = Stage 1 ; 2 = Stage 2; 3 = Stage 3; 4  = Stage 4    | 
| 2        | Training Method| 0, 1, 2, 3, 4         | 0 = None; 1 = Detect ; 2 = Exploring; 3 = Think_cot ; 4 = Thinking_RL             |
| 3        | Ablation Type  | 0, 1, 2, 3, 4         | 0 = None; 1 = Content; 2 = Visual; 3 = Audio; 4 = Other/Combined   |
| 4        | Dataset        | 0, 1, 2, 3, 4         | 0 = Defaul; 1 = VE8; 2 = YF6; 3 = VAD; 4 = Other               |
| _desc    | Description    | direct, shot, etc.    | (Optional) Brief description                                       |


## Evaluation
