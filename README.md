# Torque Python

## Installation
```shell
pip install torque-python
```

## Initialization
```python
from torque import Torque, CustomerConfig, TorqueConfig

torque_instance = \
    Torque(
        TorqueConfig(),
        CustomerConfig(
            api_secret_key='YOUR_SECRET_API_KEY'
        )
    )

```