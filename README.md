# WandbExperiment

In this experiment, we utilize Weight & Bias (WandB) for logging and tracking while tuning the hyperparameters of the XG Boost algorithm. Our goal is to optimize the model's performance by adjusting various hyperparameters and monitoring the effects.

## Hyperparameters

We explored the following ranges for our hyperparameters:
- **Learning Rate (LR)**: [0.01, 0.1, 1, 10]
- **Max Depth**: [5, 6]

## Results

You can view detailed logging and results of our experiments at the page https://api.wandb.ai/links/khatgarh-aastha0014/s6pklf5i

### Best Parameters

The optimal settings found through our experimentation are:
- **Learning Rate (LR)**: 0.01
- **Max Depth**: 5

### Performance

The best performance achieved with the optimal parameters is an RMSE (Root Mean Square Error) of **535.164**. This is an improvement over the baseline performance (RMSE of 549.104), with an **improvement of approximately 2.5%**.
