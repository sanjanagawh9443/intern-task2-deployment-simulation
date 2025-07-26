# intern-task2-deployment-simulation

# 🚀 Task 2: CI/CD Simulation Agent

This task simulates a fake CI/CD deployment system.

###  Files Included:
- `deployment.py`: Python script that simulates a fake deployment using random success/failure
- `deployment_log.csv`: Log file containing all simulated deployments


### 📈 Output:
Every time you run `deployment.py`, it logs:
- ✅ Deployment status (success/failure)
- ⏱️ Response time
- 🕒 Timestamp

###  Sample Output (deployment_log.csv):

| timestamp              | result   | response_time |
|------------------------|----------|----------------|
| 2025-07-27 13:01:14    | success  | 1.45           |
| 2025-07-27 13:03:59    | failure  | 2.12           |
| 2025-07-27 13:05:33    | success  | 1.03           |

---

> Run the script using:
> ```bash
> python deployment.py
> ```

Each time you run it, a new log will be added in `deployment_log.csv` ✅



