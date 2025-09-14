# Knowledge Tracing Implementations

## Quick Setup

### Requirements Management with pip-tools
```bash
# 1. Install pip-tools
pip install pip-tools

# 2. Create requirements.in with your dependencies

# 3. Generate locked requirements.txt
pip-compile requirements.in

# 4. Install dependencies
pip-sync requirements.txt
```